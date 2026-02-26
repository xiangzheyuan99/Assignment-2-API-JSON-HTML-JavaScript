## US Population Analytics

A data visualization tool that retrieves and displays US demographic trends.


### Core Features

* Real-time Data Sync: Fetches live population statistics directly from the **DataUSA API**.
* Graceful Degradation: Includes a built-in fallback dataset to ensure the UI remains functional even if all network proxies are blocked.
* Modern Interface: Features a Glassmorphism design with Inter typography, smooth animations, and a responsive layout.
* Interactive Controls: Seamlessly filter by year and toggle chronological/reverse-chronological sorting.


<img width="1103" height="634" alt="屏幕截图 2026-02-25 200811" src="https://github.com/user-attachments/assets/886dd4f3-b6c1-489a-9835-660e6db946c2" />

<img width="889" height="625" alt="屏幕截图 2026-02-25 200907" src="https://github.com/user-attachments/assets/b4ef1ce5-a1b1-476b-8fea-38ba2ea975a9" />


### Getting Started

Since the application relies on external API calls, running it through a local server is recommended to avoid origin-related issues.

1. Clone or Download: Save the `index.html` file to your machine.
2. Launch Local Server:
* Open your terminal in the file's directory.
* Run: `python -m http.server 8000`
3. Access: Open `http://localhost:8000` in your web browser.

### UI Architecture
The interface is built with a "Performance-First" mindset:
* Inter Typography: Optimized for legibility.
* Staggered Animations: Rows animate individually upon data load for a premium feel.
* Visual Bars: Population counts are accompanied by dynamic trend bars for instant data comparison.
