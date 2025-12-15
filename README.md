# ✈️ Wanderlust

A full-stack hotel listing marketplace where users can browse, review, and list vacation rentals. This platform allows users to view accommodations with detailed descriptions, real-time pricing, and interactive location maps.

Check out the live application deployed on Render:
👉 **[View Deployed Site](https://wanderlust-n4j0.onrender.com/listings)**

---

## ✨ Features

* **Property Listings:** Users can view a dynamic list of hotels and vacation rentals with images, prices, and descriptions.
* **Interactive Maps:** Integrated **Mapbox API** to visualize property locations on an interactive map.
* **Form Validation:** Robust client-side and server-side validation to ensure secure and correct data entry for new listings.
* **CRUD Operations:** Full Create, Read, Update, and Delete functionality for property management.
* **Responsive Design:** Optimized for mobile and desktop viewing using Bootstrap.

---

## 🛠️ Tech Stack

**Frontend:**
* HTML5, CSS3
* JavaScript (ES6+)
* ReactJS / EJS (Embedded JavaScript Templates)
* Bootstrap 5

**Backend:**
* Node.js
* Express.js

**Services & APIs:**
* Mapbox API (Geocoding & Maps)
* Render (Deployment)

---

## ⚙️ Installation & Run Locally

Follow these steps to set up the project locally on your machine.

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/wanderlust.git](https://github.com/your-username/wanderlust.git)
    cd wanderlust
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Set up Environment Variables**
    Create a `.env` file in the root directory and add the following keys (you will need your own API keys):
    ```env
    PORT=8080
    MAPBOX_TOKEN=your_mapbox_public_token
    ATLASDB_URL=your_mongodb_connection_string
    SECRET=your_session_secret
    ```

4.  **Start the server**
    ```bash
    node app.js
    # or if using nodemon
    nodemon app.js
    ```

5.  **Visit the App**
    Open your browser and go to: `http://localhost:8080/listings`

---

## 📸 Screenshots
Home-Wanderlust
<img width="1900" height="871" alt="Image" src="https://github.com/user-attachments/assets/a57813f5-c995-41c8-b5d3-9fa5caac52f1" />


<img width="1898" height="872" alt="Image" src="https://github.com/user-attachments/assets/f1771f98-a538-4334-b35d-54bbe11b77d0" />

<img width="1915" height="869" alt="Image" src="https://github.com/user-attachments/assets/c577e496-61ff-4c74-b212-3c44fc8a26fe" />

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📝 Contact

Created by **Jitendra Devra** - feel free to contact me!

* **GitHub:** [Jitendra-Devra](https://github.com/Jitendra-Devra)
* **Email:** jitudevra02468@gmail.com
