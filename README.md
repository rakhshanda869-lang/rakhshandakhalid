# AURELIA JEWELS — Full Stack
Customer-facing React + Three.js/R3F 3D showroom, plus Express/MongoDB-ready backend.

Run backend:
cd server
npm install
copy .env.example .env
npm run dev

Run frontend in another terminal:
cd client
npm install
npm run dev

Production frontend:
cd client
npm run build
Upload client/dist to Hostinger public_html. The Express backend must run as a Node.js application and connect to MongoDB for persistent products/orders.
