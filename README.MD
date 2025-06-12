PROJECT INSTRUCTIONS

#Install Dependencies

in the project terminal:
npm install --legacy-peer-deps

in another terminal:
cd .\clip-search\
pip install numpy
pip install uvicorn
pip install faiss-cpu
pip install fastapi uvicorn
pip install pandas
pip install git+https://github.com/openai/CLIP.git
pip install sentence-transformers
pip install python-multipart
pip install fastapi uvicorn torch torchvision ftfy regex tqdm faiss-cpu pillow numpy

################################

#Database Initiation

npx prisma generate
npx prisma studio

###############################

#Server Initiation

in another terminal:
npm run dev

###############################

To start ImageSearch AI

in another terminal:
cd .\clip-search\
python -m uvicorn search_api:app --host 0.0.0.0 --port 8000

###############################

To start Matchmaking AI

in another terminal:
cd .\clip-search\
python -m uvicorn designer_api:app --host 0.0.0.0 --port 8001





IF PROJECT DOESNT RUN DOWNLOAD WITH DEPENDENCIES INSTALLED : https://drive.google.com/file/d/1NVehslmr7sf-_mHSLBYys-qv52Iu4hhk/view?usp=sharing