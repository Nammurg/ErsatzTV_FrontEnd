# ErsatzTV_FrontEnd 

A self-hosted, modern IPTV web client designed to work seamlessly with **ErsatzTV**. This frontend provides an intuitive interface for streaming your favorite channels, managing categories, and accessing program schedules (EPG).

---

## Features

- **Channel Management**: Dynamically load and display channels by category.
- **Customizable Player**: Integrated video player with HLS.js for adaptive streaming.
- **EPG Support**: View current and upcoming programs with real-time progress tracking.
- **User-Friendly Design**: Sleek, responsive layout optimized for desktops and tablets.

---

## Installation

### Prerequisites

- ErsatzTV with an accessible M3U and XMLTV endpoint.
- A web server to host the HTML file (e.g., Nginx, Apache, or any static file server).

### Steps

1. Clone or download the repository:
   ```bash
   git clone https://github.com/Nammurg/ErsatzTV_FrontEnd.git
   cd ErsatzTV_FrontEnd
2. Modify the BASE_URL in the <script> section of the HTML file to point to your ErsatzTV instance:
   ```javascript
    const BASE_URL = "https://your-ersatztv-instance.com";
4. Deploy the index.html file on your preferred web server.
5. Open the deployed page in your browser to start streaming.

---


## Screenshots
### Main Interface
- Left Panel: Browse channels grouped by categories.
- Right Panel: Watch live streams and view EPG data of current channel.
![image](https://github.com/user-attachments/assets/cdf55b33-0a09-47fe-8a5f-bc48a32c007a)

### Tablet/Small Screen Interface
- Fully responsive design for smooth navigation on tablets and larger phones.
![image](https://github.com/user-attachments/assets/618b41f3-9209-4bae-b4a6-93a9033536c2)

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.


