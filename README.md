# Revolutionizing-Blog-Writing-with-AI-Harnessing-CrewAI-Multi-Agent-System
## Building 4 seperates agents
    resercher
    planner
    writer
    editor
    
## Defining seperate Tools for Agents
    ScrapeWebsiteTool()
    DirectoryReadTool()
    SerperDevTool() - used the serper API
    CSVSearchTool()
    
## Defining each seperate Tasks
    research_task
    planning_task
    writing_task
    editing_task
    
## Writing a blog regarding analysis of world happiness report
    - Introduction - what is the world happiness report. and how it is calculated. what are the factors helps to determine the world happiness of each countries.
    - should compare the previous world happiness reports with 2024 world happiness report. should provide a analysis.
    - should talk about a particular country's position in 2024 and previous world happiness reports. should provide a clear analysis 
         regarding the it's position. for this it may use the values in the csv file and the pdf file of 2024 report.
    - should talk about the how to increase that country's position in coming years and what are the changes need to be done.
    - finally it write the conclusion
## Inputs
    csv file
    website url
    country
