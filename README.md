<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> The Trace is a comprehensive system designed to streamline investigations and provide valuable tools to enhance the investigative process. It enables individuals to track ongoing cases and stay informed about the country’s mission to reduce crime. Equipped with advanced AI-powered features such as statement analysis, chat assistance, and suspect sketching tools, it empowers investigators to enhance their efficiency and significantly improve their chances of solving cases effectively.

## User Stories

### Public User

- As a public user, I want to view public cases so that I can stay informed about ongoing investigations.
- As a public user, I want to submit tips to investigators so that I can contribute to solving cases.
- As a public user, I want to comment on cases and participate in the community so that I can share my thoughts and engage with others.

### Investigator

- As an investigator, I want access to advanced tools like AI statement analysis, chat assistance, and suspect sketching so that I can enhance my investigative efficiency.
- As an investigator, I want to manage private cases so that I can maintain confidentiality while working on sensitive investigations.
- As an investigator, I want to add suspects, witnesses, evidence, and statements so that I can organize and document case details effectively.

### Admin

- As an admin, I want full access to all website features so that I can effectively manage the platform.
- As an admin, I want to manage users, cases, and settings so that the system runs smoothly and securely.
- As an admin, I want to assign cases to investigators and scrape news for relevant case information so that I can streamline case management and gather additional insights.

<br><br>

<!-- Tech stack -->
<img src="./readme/title3.svg"/>

### The Trace is built using the following technologies:

- This project uses the [React.js](https://reactjs.org/) library along with [Redux](https://redux.js.org/) for building an interactive user interface and managing global state.
- For the backend, the project utilizes [Node.js](https://nodejs.org/) with [Express.js](https://expressjs.com/) to handle API management, authentication, and server-side logic.
- The platform stores data in a [MongoDB](https://www.mongodb.com/) database, which is ideal for flexible and scalable data management.
- To provide AI-driven cognitive and behavioral insights, the platform integrates with the [OpenAI API](https://openai.com/) for advanced data processing.
- The platform is deployed and hosted on [AWS](https://aws.amazon.com/) for scalable and secure cloud infrastructure.

<br><br>

<!-- UI UX -->
<img src="./readme/title4.svg"/>

> We designed The Trace using wireframes and mockups, refining the layout to ensure seamless navigation and an intuitive user experience for public users, investigators, and admins.

- Project Figma design [figma](https://www.figma.com/design/mjeu566OyQ5Dhj0wmGkPNO/Ahmad-Ibrahim---Assignments?node-id=480-2789&p=f&t=Zf0y69twQXMyYaqX-0)

### Mockups

 
| Investigator Dashboard Screen                          | Suspect Details Screen                               |
| ---------------------------------------- | ----------------------------------------- |
| ![Investigator](./readme/figma/investigator.png)  | ![Suspect](./readme/figma/suspect.png)       |

<br><br>


<!-- Database Design -->
<img src="./readme/title5.svg"/>

### Architecting Data Excellence: Innovative Database Design Strategies:


| Case Model                          | User Model                               | Testimonial Model                               |
| ---------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| ![Case](./readme/models/case-model.png)  | ![User](./readme/models/user-model.png)       | ![Testimonial](./readme/models/testimonial-model.png)       |


<br><br>

<!-- Implementation -->
<img src="./readme/title6.svg"/>

### User Screens

| Landing Screen                           | User Profile                               |
| ---------------------------------------- | ----------------------------------------- |
| ![Landing](./readme/assets/landing-page.gif)  | ![User-profile](./readme/assets/user-profile-page.gif)|
| Public Cases                           | Case Details                            |
| ![Public-cases](./readme/assets/cases-page.gif)  | ![Case-details](./readme/assets/case-page.gif)      |

### Investigator Screens

| Investigator Cases                           | Investigator's Case Details                              |
| ---------------------------------------- | ----------------------------------------- |
| ![Investigator-cases](./readme/assets/investigator-cases.gif)  | ![Investigator-case](./readme/assets/investigator-case.gif)|
| Investigator's Stats                           | Investigator's Case Dashboard                           |
| ![Investigator-stats](./readme/assets/investigator-stats-page.gif)  | ![Case-dashboard](./readme/assets/investigator-case-dashboard.gif)      |
| Suspect Details                           | Witness Details                           |
| ![Suspect-details](./readme/assets/suspect-details.png)  | ![Witness-details](./readme/assets/witness-details.png)      |
| Suspect Statement                           | Witness Statement                           |
| ![Suspect-statement](./readme/assets/suspect-statement.png)  | ![Suspect-statement](./readme/assets/witness-statement.png)      |
| Evidence Details                           | Suspect Sketch                           |
| ![Evidence-details](./readme/assets/evidence-details.png)  | ![Suspect-sketch](./readme/assets/suspect-sketche.png)      |
| AI Suspect Sketch                           | AI Statement Analysis                           |
| ![AI-suspect-sketch](./readme/assets/AI-suspect-sketch.gif)  | ![AI-statement-analysis](./readme/assets/AI-statement-analysis.gif)      |
| Investigator GPT                           |                           |
| ![InvestigatorGPT](./readme/assets/InvestigatorGPT.gif)  | ![fsdaf](./readme/assets/suspect-sketche.gif)      |

### Admin Screens

| Admin Dashboard                           | Manage Investigators                              |
| ---------------------------------------- | ----------------------------------------- |
| ![admin-dashboard](./readme/assets/admin-dashboard.png)  | ![manage-investigators](./readme/assets/manage-investigators.png)|
| Manage Cases                           | Manage-users                           |
| ![manage-cases](./readme/assets/manage-cases.png)  | ![manage-users](./readme/assets/manage-users.png)      |


<br><br>

<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

### Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project utilizes advanced prompt engineering techniques to optimize interactions with the OpenAI API, aiming to assist in solving crime cases. By carefully crafting input prompts, we tailor the research process to generate precise insights, enhancing the accuracy and effectiveness of criminal investigations.

<div style:"display:flex">
 <img src="./readme/assets/investigatorGPT-prompt.png" width="500px"/>
 <img src="./readme/assets/ai-statement-prompt.png" width="500px"/>
</div>

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

### Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project utilizes AWS deployment strategies to build a robust and scalable backend for The Trace. By leveraging the capabilities of AWS services, we ensure that our advanced investigative tools, such as AI-driven statement analysis, are delivered efficiently to support investigators, the public, and government admins.
- **API Documentation**: Detailed API documentation can be accessed through [Postman](https://documenter.getpostman.com/view/39957658/2sAYQcGWcA).

| Get Cases API                                   | Analyze Statement API        |
| ------------------------------------------- | ----------------------------------------- |
| ![Cases](./readme/APIs/get-cases.png)      | ![Statement](./readme/APIs/ai-statement-analyze.png) |
| Add Suspect API                              | Add Suspect Statement API                   |
| ![Suspect](./readme/APIs/add-suspect.png)   | ![Suspect-statement](./readme/APIs/add-suspect-statement.png) |

<br><br>


<!-- How to run -->
<img src="./readme/title10.svg"/>


> To set up The Trace locally, follow these steps:


## Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Node.js** (v16+ recommended)
- **npm** or **yarn** (for package management)
- **MongoDB** (running locally or on a cloud service)
- **OpenAI API Key** (Sign up at [OpenAI](https://platform.openai.com/) to get your API key)

---

## Steps to Run the Project

### 1. Clone the Repositories

```bash
# For Backend/Server Side:
git clone https://github.com/AhmadIbrahim01/the-trace-backend.git
cd the-trace-backend

# For Frontend/Client Side:
git clone https://github.com/AhmadIbrahim01/the-trace-frontend.git
cd the-trace-frontend
```

### 2. Install Dependencies

#### For Backend:

```bash
npm install
```

#### For Frontend:

```bash
npm install
```

---

### 3. Set Up Environment Variables

Create a `.env` file in both the `the-trace-backend` and `the-trace-frontend` directories and add the following variables:

#### In `the-trace-backend/.env`:

```plaintext
SERVER_PORT=8000

DB_NAME=thetracedb
DB_HOST=mongodb://127.0.0.1
DB_PORT=27017
DB_USER=
DB_PASSWORD=

JWT_SECRET=secretahmad

OPENAI_API_KEY=your-openai-api-key
```

#### In `the-trace-frontend/.env`:

```plaintext
VITE_SERVER_PORT = 8000
```

Replace `your-openai-api-key` with your actual OpenAI API key and `thetracedb` with your MongoDB database name.

---

### 4. Start MongoDB

Ensure MongoDB is running on your system:

```bash
mongod
```

Alternatively, use a cloud service like MongoDB Atlas.

---

### 5. Run the Backend

Navigate to the `the-trace-backend` directory and start the server:

```bash
cd the-trace-backend
npm start or npm run start:dev
```

---

### 6. Run the Frontend

Navigate to the `the-trace-frontend` directory and start the React app:

```bash
cd the-trace-frontend
npm run dev
```

---

### 7. Access the Application

- Open your browser and navigate to [http://localhost:5173](http://localhost:5173).

---


## Troubleshooting

1. **MongoDB connection error**: Ensure MongoDB is running and `MONGO_URI` is correctly configured.
2. **OpenAI API errors**: Check your API key and ensure your usage limit hasn't been exceeded.
3. **Frontend not connecting to backend**: Verify that the `REACT_APP_BACKEND_URL` in the frontend `.env` file matches the backend server's URL.
