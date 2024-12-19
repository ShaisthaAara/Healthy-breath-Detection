This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Healthy Breathe Detection Transformer
Developed a transformer-based AI model that analyzes lung sound recordings to detect respiratory conditions early. By capturing long-range dependencies in spectrograms, our model identifies subtle abnormalities that traditional stethoscope methods often miss.

# Demo Video
Watch the demo video to see Healthy-Breath-Detection in action!

# Installation Instructions
Frontend (Next.js)
Clone the repository

git clone https://github.com/tauseef-2611/Healthy-Breath-Detection.git
cd Healthy-Breath-Detection/frontend
Install dependencies

npm install
Run the development server

npm run dev
Open http://localhost:3000 with your browser to see the result.

Backend (Flask API)
Navigate to the backend directory

cd ../backend
Create a virtual environment

python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies

pip install -r requirements.txt
Run the Flask API

flask run
The API will be running on http://localhost:5000.

Project Structure
Healthy-Breath-Detection/
├── frontend/           # Next.js frontend application
│   ├── components/     # React components
│   ├── pages/          # Next.js pages
│   ├── public/         # Public assets
│   └── styles/         # CSS styles
│
├── backend/            # Flask API for model connection
│   ├── app.py          # Main Flask application
│
├── README.md           # Project readMe file
└── requirements.txt    # Backend dependencies
Contributing
We welcome contributions! Please fork the repository and submit pull requests.

License
This project is licensed under the MIT License. See the LICENSE file for details.

