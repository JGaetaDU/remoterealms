# Remote Realms XP and Farming Calculator

This project is a *web-based calculator* designed to support players of **Remote Realms** in planning farming progression and understanding **experience (XP)** systems. It brings together *community-generated knowledge*, gameplay observation, and structured data to create a practical tool for in-game decision-making.

## Purpose

**Remote Realms** is an RPG focused on *skill training, gathering, crafting,* and long-term progression. While the game includes complex systems, it does not clearly communicate XP requirements or optimal farming strategies. As a result, players rely on shared knowledge and experimentation.

This project organizes that information into a **structured dataset** and an accessible calculator that allows players to:

- Plan **farming XP progression**  
- Compare crop **experience values**  
- Estimate **seed requirements**  
- Map leveling paths from current to target levels  
- Use either *level-based* or *total XP-based* input  

## Dataset Overview

The project includes two primary datasets:

### Experience Dataset
- Levels *1–99*  
- Total **cumulative XP** required per level  
- XP required to reach the next level  
- Supports both *forward* and *reverse* calculations  

### Farming Dataset
- Crop name  
- Patch type  
- Level requirement  
- Seeds required  
- Planting XP  
- Harvest XP  
- Estimated XP per cycle  

**XP per cycle** is calculated as:

*Plant XP + Harvest XP*

The datasets are stored as **CSV files** and integrated into the calculator for interactive use.

## Methodology

Data was collected through a combination of:

- Player-maintained *wiki resources*  
- Community discussion (*Discord and in-game chat*)  
- Direct gameplay observation and testing  

A **triangulated approach** was used to improve reliability. Values were considered verified when they were consistent across multiple player reports and reproducible through gameplay.

Community feedback played a key role in refining both the dataset and the calculator. Early versions were shared with players, and their input informed improvements to **data structure**, **calculation logic**, and **usability**.

## The Calculator

The calculator translates structured datasets into an interface that supports *practical use during gameplay*. It allows players to estimate XP requirements, compare crops, and plan farming cycles using consistent baseline values.

Hosting the tool on **GitHub Pages** allows players to access it without needing to download or maintain their own copies, while also supporting **transparency** and **version tracking**.

## Access

**Live Calculator:**  
https://jgaetadu.github.io/remoterealms/

**Repository:**  
https://github.com/jgaetadu/remoterealms

## Project Status and Privacy

At the time of this project, the calculator has not been broadly released. Access has been shared with a small group of *trusted players* for testing and feedback.

A future version will be deployed through a separate repository that removes *personally identifiable information* to support wider public access.

## Reuse and Licensing

The dataset is derived from *observable gameplay* and publicly shared community knowledge. It is intended for **educational and community use**.

A formal license has not yet been applied. Future versions will include a **Creative Commons license** to clarify reuse and attribution.

## Limitations

- Data is based on *player observation* rather than official game documentation  
- Some values remain incomplete as testing continues  
- *Compost mechanics* are not included due to inconsistent results  
- The calculator reflects **baseline XP estimates** using plant and harvest values only  

Results should be interpreted as *planning estimates* rather than exact maximum outcomes.

## Future Development

Potential future improvements include:

- Incorporating additional mechanics once reliable data is available  
- Separating datasets into external files for easier updates  
- Expanding calculator features  
- Supporting broader public release  

## Acknowledgments

This project is built on the contributions of the **Remote Realms player community**. Shared observations, testing, and feedback were essential in shaping both the dataset and the calculator.
