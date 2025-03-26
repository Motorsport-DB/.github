# MotorsportDB

MotorsportDB is a project dedicated to documenting and archiving the results of all professional motorsport drivers, without expiration. Our goal is to maintain a comprehensive database that spans from the origins of motorsport to the present day.
You can see the projet here : [https://www.motorsportdb.org](https://www.motorsportdb.org)

## Scope of the Project

- Covers all professional motorsport categories, including but not limited to:
  - Karting
  - Formula 1
  - Endurance racing (Le Mans, WEC, etc.)
  - NASCAR
  - IndyCar
  - MotoGP
  - WRC (World Rally Championship)
- Focus on accuracy over recency: our priority is to ensure that all data is correct and reflective of official results.
- No personal opinions or subjective judgments: only factual data from official sources.
- Official results are sourced from the FIA or relevant race organizers.

## Repository Structure

- **website/**: Contains everything related to the website, including scripts, result displays, and statistical calculations. You can clone this repository directly into:
  - `C:\wamp64\www` (Windows with WAMP)
  - `/var/www/html` (Linux with Apache2 and PHP installed)

- **drivers/**: Contains results and information about each driver, including career history, photos, and social media links. Future plans include adding biographies and detailed achievements.

- **teams/**: Stores information on team results and performance history.

- **races/**: Maintains championship results and race data.

The repository structures may evolve to improve usability and data integration.

## Contribution Guidelines

To maintain consistency and quality, contributions must follow these rules:

- Only professional championships are allowed (local amateur karting does not qualify).
- Images must be copyright-free or officially provided by drivers, teams, or organizers.
- Partial data is acceptable as long as it is accurate.
- All commits must be signed (see the collaboration section below).

## How to Collaborate

1. Clone the repositories:
   ```sh
   # Clone the website repository
   git clone https://github.com/motorsportdb/website.git
   cd website
   ```
   - Place it in:
     - Windows: `C:\wamp64\www`
     - Linux: `/var/www/html`

2. Clone the other repositories inside the website directory:
   ```sh
   git clone https://github.com/motorsportdb/drivers.git
   git clone https://github.com/motorsportdb/teams.git
   git clone https://github.com/motorsportdb/races.git
   ```

3. Make your modifications in JSON files or in the code.
4. Stage your changes:
   ```sh
   git add <filename>
   ```
   Example:
   ```sh
   git add index.html
   ```

5. Create a new branch for your modifications:
   ```sh
   git checkout -b feature-{short-description}
   ```
   - Choose a meaningful and descriptive branch name.

6. Commit your changes with a signed commit:
   ```sh
   git commit -s -m "Short commit title"
   
   """
   - Detailed description of changes
   - List of modifications with bullet points
   """
   ```
   - Keep commit titles under 70 characters.
   - Use bullet points for clarity in the message body.

7. Push your changes and create a pull request.

## Additional Notes

- The goal is to make contributing as easy as possible while ensuring high data accuracy.
- We encourage motorsport enthusiasts to help expand and refine the database.
- If you have questions, feel free to open an issue or contact the maintainers.

---

We appreciate your contributions to MotorsportDB! Together, we can build the most accurate and comprehensive motorsport database available.
