# Overton Window Ontology Graphic prototype

A sophisticated, interactive 3D visualization tool designed to map political narratives, policy positions, and social consensus across various domains. This application utilizes the **Overton Window** concept—the range of policies acceptable to the mainstream population at a given time—and projects them into a dynamic 3D space.

## 🚀 Overview

This single-page application (SPA) provides a multi-dimensional look at complex topics such as Health IP, Mental Health, Global AI Regimes, and Immigration. By plotting policies on an X-axis (Acceptability/Status Quo) and a user-definable Y-axis (Impact, Safety, or Feasibility), users can visualize where different interest groups collide or align.

### Key Datasets Included:

* **Commercial Access & IP in Health:** Examining the friction between patient advocacy and pharmaceutical industry interests.
* **NHS Mental Health Approaches:** Mapping the medical model vs. the social/rights-based model.
* **Global AI & IP Regimes:** Comparing the regulatory stances of the EU, USA, China, and Japan.
* **UK Foreign Policy & Immigration:** Visualizing the spectrum of political discourse in the UK.

---

## ✨ Features

* **3D Force Visualization:** Built with **Three.js**, policies are rendered as icosahedron nodes that react to filtered data.
* **Dynamic Y-Axis:** Toggle the vertical dimension to see how policies rank based on Clinical Efficacy, Public Trust, Innovation Speed, or Human Rights.
* **Interactive Consensus Filters:** Shift the "Overton Window" (the translucent box) to highlight different blocks of political consensus (e.g., "Protectionism" vs. "Privatization").
* **Interest Group Filtering:** Toggle specific stakeholders (e.g., Academics, Industry, Regulators) to see which policies they support.
* **Evidence-Backed Insights:** Each node contains metadata, including concrete statistics and source links (NHS Digital, ONS, WHO, etc.).
* **Draggable Interface:** A custom React-based control panel and tooltip system that stays out of the way of the visualization.

---

## 🛠️ Tech Stack

* **Frontend:** React (v18)
* **3D Engine:** Three.js (r128)
* **Styling:** Tailwind CSS
* **Transpilation:** Babel (Standalone)
* **Icons/Typography:** Google Fonts (Inter & Playfair Display)

---

## 📖 Usage

1. **Select Ontology:** Use the dropdown in the Control Panel to switch between topics (e.g., "AI in Healthcare").
2. **Navigate the Space:** Hover over 3D nodes to see a quick preview. Click a node to "pin" the detailed evidence tooltip.
3. **Filter Narratives:** Use the "Consensus Filter" to move the teal box across the spectrum, identifying which policies are currently "Policy" vs. "Unthinkable."
4. **Analyze Evidence:** Scroll down to the **Narrative & Policy Index** to read the full descriptions and supporting statistics for every record in the current view.

---

## 📊 Sample Data Insights

The app includes significant data points such as:

* **Mental Health:** Black people in the UK are **11x more likely** to be placed on a Community Treatment Order (CTO) compared to white people.
* **Health Data:** NHS data value is estimated at **£9.6bn/year** to the commercial sector.
* **AI Regulation:** The Nightshade tool can "poison" AI training data with as few as **50 images**, protecting artist styles.

---

## 🔧 Installation & Deployment

This is a "zero-install" application. Because it uses CDN-hosted libraries, you can run it simply by opening the `index.html` file in any modern web browser.

```bash
# Clone the repository
git clone https://github.com/your-repo/overton-ontology.git

# Open in browser
open index.html

```

Would you like me to add a section on how to add a new custom dataset to the `DATASETS` object?
