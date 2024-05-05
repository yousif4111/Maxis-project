


[![LinkedIn][linkedin-shield]][linkedin-url]



<h1 align="center">Propensity Model Fibre WBB</h1>

<img align="center">![image](https://github.com/othneildrew/Best-README-Template/assets/46527978/80b3aa56-472a-4c00-b540-a5cedbcb1180)</img>

## Problem Statment

One of the most essential products provided by telecom companies is **Fiber Internet**. 🌐💨

Our Marketing Department they wanted analyticals and AI solution to **improve their conversion rate on telesales calls** for this product. ☎️ 

One solution we developed for them was a propensity model **to score our customer base based on their willingness to subscribe to our fiber service**, which can help the staff in this department reach out to targeted groups faster and increase their conversion rate. 📈🎯

![image](https://github.com/yousif4111/Maxis-project/assets/46527978/69cc5394-05f7-45d8-8462-2d0cff71c841)





## Data 

The data that is used is intellectual property; however, here is a general description of the kind of data used: 📊🔒

1. Previous Service Usage: The customer's history of using internet services, such as previous subscriptions, duration, and data usage. 📶📆📊
2. Internet Speed Preference: The customer's preference for faster internet speeds and their previous experiences with different speeds. ⚡📶
3. Demographic Information: Age, gender, location, and income level can provide insights into customer preferences and purchasing power. 👨‍👩‍👧‍👦📍💰
4. Current Internet Service Provider: The customer's existing internet service provider and their level of satisfaction with the service. 🌐🏢😊
5. Online Activities: The types of online activities the customer engages in, such as streaming, gaming, remote work, or online education. 🎥🎮💼📚
6. Social Media Presence: The customer's engagement on social media platforms indicates their online presence and potential interest in high-speed internet. 📱💻🌐
7. Household Size: The number of people in the customer's household who would benefit from fiber internet service. 👨‍👩‍👧‍👦
8. Technological Affinity: The customer's comfort level and familiarity with technology, including devices used, software proficiency, and willingness to adopt new technologies. 🖥️💡💻
9. Competitor Offerings: Awareness of and interest in competitor fiber internet offerings, including pricing, packages, and promotional deals. 💰💼👀

## Methadology

We trained different types of **classification models**, such as **XGboost, LightGBM**, and so on. 🌟🧪

Since we care about minimizing both false negatives and false positives, the metric that we used to evaluate the model's performance was the F1 score. This metric helps in balancing precision and recall. By focusing on maximizing the **F1 score**, you prioritize both minimizing false negatives (increasing recall) and minimizing false positives (increasing precision). This ensures that fewer potential customers who are likely to buy fiber are incorrectly classified as not likely to buy, reducing missed opportunities for conversion, while also avoiding misclassifying unlikely customers as likely, which can waste resources. ⚖️🔍

### Scoring Customer Base based on Probability to Buy Fiber:

Using the trained Model:

1- We Calculate Probability Scores: Obtain probability scores representing the likelihood of customers subscribing to fiber internet based on their input features. 📈💯

1- Rank and Segment Customers: Rank the customers based on their probability scores, allowing for segmentation into groups with different levels of likelihood to buy fiber. 📊👥

## Tools we used to deploy the model
The model we built on top of Google cloud infastructure.
here are list of tools we used:
1. BigQuery: Utilize BigQuery to store and analyze customer data, extracting relevant information for training and deploying the propensity model. 📊💾
2. Vertex AI: Leverage Vertex AI's machine learning capabilities to train the propensity model and easily deploy it for scoring predictions. 🧠🚀
3. Virtual Machine (VM): Set up a custom environment on a VM in GCP for developing and deploying the propensity model. 💻🔧
4. Cloud Storage: Store training data, model artifacts, and resources in Cloud Storage, accessible for deploying and serving the propensity model. ☁️🗄️
5. Cloud Function: Deploy a serverless Cloud Function to load the model, preprocess data, and provide real-time predictions based on customer inputs. ⚡️🔮
6. Airflow: Orchestrate the deployment workflow using Airflow, scheduling tasks such as training the model and deploying it to a production environment. 🔄📅



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/yousif-abdalla/
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

