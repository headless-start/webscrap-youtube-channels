# YouTube Channel Video Scraper  

## 📌 Project Overview  
This Python script fetches video details from a YouTube channel using the **YouTube Data API**. It retrieves information such as video titles, URLs, view counts, upload dates, durations, and descriptions. The data is saved to a JSON file for further analysis or use. The sample ouput json file contains the output I got for my YouTube channel with 3 videos. 

---

## 🚀 Key Features  
1. **YouTube Data API Integration**:  
   - Fetches video details using the YouTube Data API.  
   - Supports pagination to retrieve all videos (up to 50 per request).  
2. **Data Extraction**:  
   - Extracts video metadata: title, URL, views, upload date, duration, and description.  
3. **Efficient Data Storage**:  
   - Saves the fetched data to a JSON file (`youtube_channel_data.json`) for easy access and analysis.  

---

## 🔍 How It Works  
1. **Input**:  
   - Provide your **YouTube Data API key** and the **channel ID** of the target YouTube channel.
   - The **channel ID** is not similar to the channel handle.
   - The **channel ID** can be fetched from **https://www.googleapis.com/youtube/v3/channels?part=id&forUsername=USERNAME&key=YOUR_API_KEY**
2. **Process**:  
   - The script makes API requests to fetch video IDs and their metadata.  
   - It ensure all videos of the channel are retrieved.  
3. **Output**:  
   - A JSON file containing structured video data.  

---

## 🛠 System Requirements  
### Dependencies  
- Python 3.8+  
- Libraries: `requests`  
- **YouTube Data API key** (obtain from [Google Cloud Console](https://console.cloud.google.com/)).

---

## 📄 License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
