# back
cd back
python -m venv .venv
.venv\Scripts\activate
fastapi run

# front
cd front
npm install
npm run dev