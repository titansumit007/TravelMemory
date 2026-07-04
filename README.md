# Travel Memory




<img width="1097" height="395" alt="2  updating  apt" src="https://github.com/user-attachments/assets/85ea6cca-8ec0-4eb8-a1ca-a91f81d327af" />

<img width="1092" height="617" alt="4  installing npm in backend folder" src="https://github.com/user-attachments/assets/b6ba01f4-dd20-4980-bf07-38b7a034e924" />

<img width="1912" height="436" alt="8  backend tested via brower" src="https://github.com/user-attachments/assets/86d2eee6-7d2f-439c-9b43-f4ea4f51205c" />

<img width="1072" height="636" alt="7  moving to frontend created env" src="https://github.com/user-attachments/assets/b34249ed-b876-415a-b37c-612cb93a4180" />

<img width="1072" height="1022" alt="9 front enf started  package installed and env created" src="https://github.com/user-attachments/assets/8992c45d-d090-48b1-995c-77569d52d976" />
<img width="1462" height="821" alt="10  Nginx nstalled" src="https://github.com/user-attachments/assets/9fd88969-25ff-427d-8fa9-91e3192cfc19" />
<img width="1245" height="332" alt="11  Nginx configured and started" src="https://github.com/user-attachments/assets/34242170-502b-4a10-a3e8-a01e0971e2c2" />

<img width="1867" height="592" alt="10   App  added two entries" src="https://github.com/user-attachments/assets/574b4b5f-099f-4d66-b1d0-28242ac7cccb" />

<img width="1907" height="802" alt="13  another ec2 instance created usi AMI image" src="https://github.com/user-attachments/assets/cec7f9d6-0d71-4495-8e02-6c700f1ca225" />


<img width="1522" height="742" alt="14  started backend server in 2nd ec2 instance" src="https://github.com/user-attachments/assets/bc984a36-8bff-45aa-a773-05812c904801" />

<img width="1887" height="695" alt="Creating new target group for loadbalancer" src="https://github.com/user-attachments/assets/62d0d1d3-d7bc-45fd-86b4-0f70b697930d" />

<img width="1842" height="781" alt="15 target group set up done" src="https://github.com/user-attachments/assets/091ad411-87f5-4e0e-9f03-20955e2a01a7" />

<img width="1902" height="882" alt="16 load balancer set up done" src="https://github.com/user-attachments/assets/e48998c3-924a-40a7-82b6-3ef68728b25c" />

<img width="1902" height="432" alt="17  Load balancer setup done" src="https://github.com/user-attachments/assets/b9cdd06b-f357-4f4a-8432-c174d00f84a0" />


<img width="1901" height="802" alt="17  Load balancer setup working" src="https://github.com/user-attachments/assets/31921757-91e9-4afa-84db-0c253c5ae6a8" />

<img width="1876" height="810" alt="20  Validation of app with domain app" src="https://github.com/user-attachments/assets/09e6af7a-4092-4604-83b5-47ad0c55a02e" />

<img width="1567" height="770" alt="18  DNS records for Domain" src="https://github.com/user-attachments/assets/76baa87d-81b1-4214-a58e-ee5102bbc7b1" />

<img width="1822" height="887" alt="19  direct ip domain is working fine" src="https://github.com/user-attachments/assets/a3bcbba0-2f73-452a-a8d7-e7684f65ec88" />

<img width="1247" height="561" alt="21  Architecture" src="https://github.com/user-attachments/assets/fe1dcdf5-2137-4991-9d71-882c1c60617e" />

<img width="1500" height="617" alt="22  GIT commit" src="https://github.com/user-attachments/assets/8d8b5a75-c009-4806-84e0-1e0bfe5152cd" />

<img width="1676" height="1007" alt="22  Git pushed completed" src="https://github.com/user-attachments/assets/78b1a7a7-96b6-4843-8d10-ff3fe20b190e" />

`.env` file to work with the backend after creating a database in mongodb: 

```
MONGO_URI='ENTER_YOUR_URL'
PORT=3001
```

Data format to be added: 

```json
{
    "tripName": "Incredible India",
    "startDateOfJourney": "19-03-2022",
    "endDateOfJourney": "27-03-2022",
    "nameOfHotels":"Hotel Namaste, Backpackers Club",
    "placesVisited":"Delhi, Kolkata, Chennai, Mumbai",
    "totalCost": 800000,
    "tripType": "leisure",
    "experience": "Lorem Ipsum, Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum, ",
    "image": "https://t3.ftcdn.net/jpg/03/04/85/26/360_F_304852693_nSOn9KvUgafgvZ6wM0CNaULYUa7xXBkA.jpg",
    "shortDescription":"India is a wonderful country with rich culture and good people.",
    "featured": true
}
```


For frontend, you need to create `.env` file and put the following content (remember to change it based on your requirements):
```bash
REACT_APP_BACKEND_URL=http://localhost:3001
```

## How to run BE

Note: Make sure you have the .env file already added
```bash
cd backend
npm install
node index.js
```

## How to run FE
Note: Make sure you have the .env file already added
```bash
cd frontend
npm install
npm start
```
