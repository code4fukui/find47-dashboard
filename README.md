> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

# find47-dashboard

A web-based dashboard that visualizes the beautiful photography of the [FIND/47](https://find47.jp/) project. Explore photos from all 47 prefectures of Japan through an interactive map and an immersive slideshow viewer.

## Demo

- **[Dashboard](https://code4fukui.github.io/find47-dashboard/)**: An interactive map of Japan showing photo distribution.
- **[Keyword Search](https://code4fukui.github.io/find47-dashboard/keywoard.html)**: A tool to launch a slideshow based on a search term.

## Features

- **Interactive Choropleth Map**: Visualizes the number of photos per prefecture using a color-coded map. Each region displays its photo count and national rank.
- **Prefecture Photo Gallery**: Clicking a prefecture on the map instantly loads a thumbnail gallery of its photos below.
- **Immersive Slideshow**: Launch a full-screen, gently animated slideshow for any prefecture or for keyword search results. Photo details (title, author) are overlaid.
- **Keyword Search**: Find photos across all prefectures by a keyword (e.g., "桜", "城", "海") and view the results in a dedicated slideshow.

## How to Use

1.  **Explore the Map**: Open the [Dashboard](https://code4fukui.github.io/find47-dashboard/). The map of Japan shows the distribution of photos by prefecture.
2.  **Select a Prefecture**: Click on a prefecture to view its statistics and load a gallery of its photos at the bottom of the page.
3.  **Launch the Slideshow**: Above the gallery, click the link (e.g., "北海道 スライドショー表示へ") to open the full-screen animated slideshow for that prefecture.
4.  **Search by Keyword**: Visit the [Keyword Search](https://code4fukui.github.io/find47-dashboard/keywoard.html) page, enter a term, and click "open" to see a slideshow of matching photos from the entire collection.

## Data and Technology

- **Photo Data**: Sourced from the [FIND/47 project](https://find47.jp/), with CSV data prepared by [code4fukui/find47](https://github.com/code4fukui/find47).
- **Slideshow Viewer**: Powered by [yurayura-photo-viewer](https://github.com/code4fukui/yurayura-photo-viewer).
- **App Development**: Created by [Code for FUKUI](https://code4fukui.github.io/).

## License

This project is available under the [MIT License](LICENSE).