# Wood Transport Visualization Platform

This project is a web application developed during a hackathon that visualizes Romanian wood transport data using an interactive graph-based interface.

The application integrates a publicly available Romanian wood-transport tracking API and represents transport relationships through an expandable, force-directed graph, allowing users to explore connections between transports in an intuitive way.

---

## Original Hackathon Repository

The original source code and collaboration history can be found here:

 **Hackathon Repository:**
`https://github.com/Hackathon-TW-2025/zebrahack3-0-isoskill.git`

---

## Demo Video

Since access to the API may be discontinued in the future, a full video demonstration of the application is provided below:

**YouTube Demo:**
`https://youtu.be/OgogcdDiXX4`

---

##  Features

* Integration with a Romanian wood-transport tracking API
* Interactive, expandable force-directed graph visualization
* Company-based filtering of transport data
* Directional edge animations based on transport role

  * outgoing animation when the selected company is the **sender**
  * incoming animation when the selected company is the **receiver**
* Edge animation speed dynamically adjusted based on the **quantity of transported wood**
* Dynamic exploration of transport relationships
* Simple and responsive landing page
* Client-side rendering with no backend dependency

---

##  Technologies Used

* **HTML** – structure and layout
* **CSS** – styling and responsive design
* **JavaScript** – application logic and API integration
* **force-graph** – interactive graph visualization

---

## Data Visualization Logic

The core of the project is an interactive graph built using **force-graph**, where:

* nodes represent companies and transport-related entities
* edges represent wood transport relationships
* edge animation direction reflects whether the selected company is the sender or the destination
* animation speed visually encodes the transported wood quantity, enabling quick visual comparison

---

## API Availability Notice

The application relies on a third-party, publicly available API.
Access to this API may be limited or discontinued in the future.
For this reason, the video demo above serves as a permanent reference of the project's functionality.

---

## Hackathon Context

This project was developed as part of a hackathon collaboration.
This repository serves as a **portfolio reference**, while the original hackathon repository is linked above.

---


