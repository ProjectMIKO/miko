# MIKO
프로젝트 MIKO 를 위한 레포


# Directory Structure
```
MIKO/
├── backend/
│ ├── main-server/
│ ├── nlp-server/
├── frontend/
```

# Backend 디렉토리
MIKO 서비스의 백엔드 서버. 회의방과 화상 대화를 위한 서버와 자연어 처리를 위한 서버로 나뉨.

## Main Server
회의방, 화상 대화를 위한 서버

NestJS

### Installation
1. Navigate to the `main-server` directory:
    ```bash
    cd backend/main-server
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    npm run start:dev
    ```


## NLP Server
자연어 처리를 위한 서버

Python Flask

### Installation
1. Navigate to the `nlp-server` directory:
    ```bash
    cd backend/nlp-server
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Start the server:
    ```bash
    python app.py
    ```

# Frontend
MIKO 프론트엔드 서버

Next.js

### Installation
1. Navigate to the `frontend` directory:
    ```bash
    cd frontend
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm run dev
    ```


