# Home Labbing

This repository serves as a personal collection of configurations, cheat sheets, and Docker Compose files for setting up and managing a home lab environment.

## Table of Contents
- [Cheat Sheets](#cheat-sheets)
- [Docker Compose Setups](#docker-compose-setups)
 





## Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/omcodes23/home-labbing.git
    cd home-labbing
    ```

2.  **Use Cheat Sheets:**
    Refer to the `.txt` files in the `Cheet-Sheets` directory for command references.

3.  **Deploy Docker Services:**
    - Navigate to the desired service directory (e.g., `cd Docker-Compose/Mongo+UI/`).
    - If required, create a `.env` file with the necessary credentials (see instructions for [MongoDB + Mongo Express](#mongodb--mongo-express)).
    - Run the following command to start the services in detached mode:
      ```bash
      docker-compose up -d
      ```
    - To stop the services, run:
      ```bash
      docker-compose down
