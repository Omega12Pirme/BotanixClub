# This project is made under SpiderHack Hackathon

### THis project is under development


![image](https://github.com/Omega12Pirme/BotanixClub/assets/105157723/0edcc4ee-ecef-4e0c-98fd-321075a86859)




# Botanix Club


For years I have wanted to participate in fund initiatives to invest in projects (startups and others), but the bureaucracy, the high requirements, and many other problems make it very difficult. And it is something that not only I experience, but also many other people who have a little money and want to support projects in the medium/long term.

The exact size of the private investment fund market is difficult to determine, as there is no single, comprehensive source of data. However, it is estimated that this market has experienced significant growth in recent decades. According to Bain & Company's Global Private Equity Report 2021, assets under management in the private equity industry reached a record of approximately US$4.6 trillion in 2020. In addition to traditional private equity, there are also other types of private investment funds, such as hedge funds, venture capital funds, and private debt funds. Each of these segments has distinct characteristics and investment approaches.

Therefore, through DAO (decentralized organizations) we can create structures so that anyone can invest, through investment clubs (by affinity of ideas, professional relationship, etc.) through Blockchain from anywhere in the world and with fewer requirements. That is why Botanix Club  was born.

<br>

## 📋 Table of Contents

- [Introduction](#introduction)
- [Installation](#-setting-up-the-project-locally)
- [Challenges we ran into](#-challenges-we-ran-into)
- [Technologies we used](#%EF%B8%8Ftechnologies-we-used)
- [Video Demo](#-video-demo)
- [Contributing](#-contributing)
- 

</div>
<a href="#top">Back to top</a>




## Smart Contract deployed on Botanix Testnet  
- Smart contract -0x78cAcbc8A107B03487f5cc666fDC27c4d16c846A
- https://blockscout.botanixlabs.dev/tx/0x51a6f1e8f8c942bc3cfadac6e7a928d87bfef2226cbb7834087d22fbfb968b38



## 💡Introduction

Botanix  Club allows you to manage investment clubs, and to spread access to participate in investment funds to anyone, decentralized, agile, and without bureaucracy.Implementing a comprehensive on-chain governance system allows DataDAO members to create and vote on proposals, covering aspects such as member management, dataset storage and distribution, and token distribution. This ensures a democratic and transparent decision-making process within the DAO.

## What you can currently do in this version is:

- Create investment clubs: Just define a name and the club will be associated with the account of the user who creates it (owner).

![Screenshot from 2024-03-19 18-53-33](https://github.com/Omega12Pirme/BotanixClub/assets/105157723/c20aaf4c-40d2-49f9-80ad-e21c3d725e2b)


- Join or leave clubs: Anyone with an BTC blockchain account can join the available investment clubs, as well as leave one, with just a couple of clicks.

![Screenshot from 2024-03-19 18-54-13](https://github.com/Omega12Pirme/BotanixClub/assets/105157723/1a66e346-de7e-49c3-927a-58474ae8cede)


- Contribute to the club: Any member of a club can contribute to the common fund (pool), depositing CFX coins that can be used in proposals.

  https://blockscout.botanixlabs.dev/tx/0xdf65a92102bfc0387acb3802a080f76180067239d10c69d83b83468cb062b623

![Screenshot from 2024-03-19 18-58-25](https://github.com/Omega12Pirme/BotanixClub/assets/105157723/af7f392c-33c6-430d-ac4b-3a7e9e9e486a)


- Create and Vote on Proposals: Any member who has contributed funds to the club pool can create proposals, giving a description, amount (not to exceed the pool amount), and recipient, with a view     to investing in any business/person in a project. Also, all members can approve or reject the proposal (only one vote per member is allowed on each proposal).


![Screenshot from 2024-03-19 18-59-06](https://github.com/Omega12Pirme/BotanixClub/assets/105157723/26ebb062-0e1d-4e49-ac23-d1472cb5a483)


- Run Proposals: A proposal owner can execute a proposal (if approval is greater than rejection), which will cause the proposal amount to be sent to the specified recipient. The owner can also close   a proposal, in case of not continuing with it, either as a cancellation, publication error or to avoid sending funds.

  https://blockscout.botanixlabs.dev/tx/0x222474b5403613f8bbd59a12ad86e158254e5f2a59bf674ad0c1c66b8219dd6b

![Screenshot from 2024-03-19 19-01-21](https://github.com/Omega12Pirme/BotanixClub/assets/105157723/6ead8ecb-ce17-41bd-b88e-b703f9f3dba6)



  
- Timing voting:  After  creation of proposal there is only about 5 min time is given to the  mmeber to  vote.

![Screenshot from 2024-03-19 19-02-03](https://github.com/Omega12Pirme/BotanixClub/assets/105157723/91cd3461-7c59-4c5c-a305-c48ab7071066)

## What you can currently do in this version is:

- Create investment clubs: Just define a name and the club will be associated with the account of the user who creates it (owner).
- Join or leave clubs: Anyone with an Botanix blockchain account can join the available investment clubs, as well as leave one, with just a couple of clicks.
- Contribute to the club: Any member of a club can contribute to the common fund (pool), depositing BTC coins that can be used in proposals.
- Create and Vote on Proposals: Any member who has contributed funds to the club pool can create proposals, giving a description, amount (not to exceed the pool amount), and recipient, with a view to investing in any business/person in a project. Also, all members can approve or reject the proposal (only one vote per member is allowed on each proposal).
- Run Proposals: A proposal owner can execute a proposal (if approval is greater than rejection), which will cause the proposal amount to be sent to the specified recipient. The owner can also close a proposal, in case of not continuing with it, either as a cancellation, publication error or to avoid sending funds.


## Restrictions
The club smart contract has some restrictions, similar to real hedge funds:

- Up to 99 members per club (in many jurisdictions, such as the USA and Chile, this is the maximum limit of club members for certain purposes and types of clubs).
- Only members can participate in club instances.
- Only members who contribute funds to a club have the right to create proposals.
- Only proposal creators can execute them.


## 💥 Challenges we ran into
- Understanding Dao is very critical and took me more than 4 hours to get the best idea to build
- I faced lots of issues in smart contract as I have to manage all the funds, proposal, voting periods and many more things but at the end I enjoyed a lot during the building time.'I preferred that it was all 100% web' without a backend other than the smart contract, so any other developer or person can test it in any environment.
- Creating and testing the application takes more time and website seems to be quite slow.
    
<br>

<a href = "#top">Back to top</a>



### 	▶️ Experience the Live Site by Clicking the Link Below
<br>
<div align="center">
  <table>
    <tr>
      <th>Deployed On</th>
      <th>URL</th>
    </tr>
    <tr>
      <td>Vercel</td>
      <td>
       https://botanix-club.vercel.app/
      </td>
    </tr>
    </tr>
    </table>
    
</div>

<br><br>

## 🚀 Setting up the project locally

To run the  Botanix Club locally, follow these steps:
1. Clone the repository:
 ```bash
https://github.com/Omega12Pirme/BotanixClub.git
 ```
 2. Navigate to the project directory:
```bash
cd  BotanixClub
```
3. Node Re-versioning

```bash
export NODE_OPTIONS=--openssl-legacy-provider
```

4. Install the dependencies:
```bash
npm install --legacy-peer-deps
```

6. Access the dApp:
```bash
npm start
```
Open your web browser and visit the URL SHOWING IN UR TERMINAL to interact with the Botanix CLUB

<br>

## 🛠️Technologies we used


[![Powered by Lighthouse](https://img.shields.io/badge/Powered_by-Lighthouse-ff69b4?logo=lighthouse)](https://lighthouse.filecoin.io/)
[![Built with React.js](https://img.shields.io/badge/Built_with-React.js-61DAFB?logo=react)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Styled_with-Tailwind_CSS-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Powered by Ethereum](https://img.shields.io/badge/Powered_by-Ethereum-3C3C3D?logo=ethereum)](https://ethereum.org/)

| Technology        | Description                                                | Official Website                                     |
|-------------------|------------------------------------------------------------|------------------------------------------------------|
| React.js          | JavaScript library for building user interfaces, often used for server-rendered or statically-generated applications | [React.js](https://reactjs.org/)                      |
| Tailwind CSS      | Utility-first CSS framework for building custom designs   | [Tailwind CSS](https://tailwindcss.com/)              |
| Solidity | Programming language used for smart contract development on the Ethereum blockchain | https://docs.soliditylang.org/ |
|LightHouse | Store file Secure, Reliable, & Lightning-Fast with Lighthouse. |https://www.lighthouse.storage/|
|Botanix CLub| Botanix Labs is building a fully decentralized EVM ecosystem on Bitcoin powered by the Spiderchain that unlocks the largest capital pool in crypto.|https://botanixlabs.xyz/en/home|



<be>


## 🎥 Video Demo

https://youtu.be/RqvKcSqcLBo?si=78AmrnWvzNibGghY


## 🤝 Contributing

Contributions to TreasryAvlanch are always welcome! If you'd like to contribute, please follow these guidelines:
Fork the repository.

Create a new branch for your feature or bug fix:

```
git checkout -b feature/your-feature-name
```
Commit your changes:

```
git commit -m 'Add some feature'
```
Push the branch:

```
git push origin feature/your-feature-name
```
Open a pull request.

We appreciate your contributions and thank you for helping us improve Algo-Media!

<br >
</div>

## LICENSE

```
MIT
```

  
   
</div>
<a href="#top">Back to top ⬆️</a>

