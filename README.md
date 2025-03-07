
# AI Powered Project Planner

This project sets up an AI-powered workflow for Project Planning using CrewAI, and OpenAI's GPT-4o-mini. This project utilizes CrewAI to streamline project planning, task breakdown, time estimation, and resource allocation.

## Features
- **AI-Powered Task Planning**: Uses CrewAI agents to automate project planning.
- **Structured Task Estimation**: Utilizes Pydantic models for structured outputs.
- **Dynamic Resource Allocation**: Ensures optimal allocation of team members and resources.
- **Flexible Configuration**: Supports YAML-based task and agent definitions.

## Setup Instructions

1. Clone the Repository

```
git clone https://github.com/Piyal-Banik/LLM-Powered-Project-Planner.git
```

2. Install Dependencies
Make sure you have Python 3.8+ installed. Then, install the required packages:

```
pip install crewai pydantic pandas pyyaml
```

## Project Structure
```
📂 LLM-Powered-Project-Planner/
│── agents.yaml                             # Agent configurations  
│── tasks.yaml                              # Task definitions  
│── project_planner_agent.ipynb             # Main execution file  
│── README.md                               # Project documentation  
```

##  Expected Workflow
- Load YAML configurations for agents and tasks.
- Initialize CrewAI Agents for project planning, estimation, and resource allocation.
- Define structured outputs using Pydantic models.
- Execute the AI-driven project plan, with estimated tasks and milestones.
- Output results as a structured DataFrame.

## Example Output
The example provided in ```project_planner_agent.ipynb``` outlines a Website Development Project in the Technology Industry, with objectives, team members, and detailed requirements. The CrewAI system will generate structured task estimates and milestone planning based on this input.