# NFTFlex

Social Media Embed for Solana NFTs with Ownership Display & Liquidating an NFT to Any Token.

## ⚠️ Problem to Solve.

There is a growing demand for easy ways to showcase Solana NFTs on social media platforms, along with information about the current owner's Twitter handle. Existing solutions do not provide a simple URL that generates a summary card with a large image and ownership information, making it difficult for users to share and display their NFTs on social media.

## ✅ Possible Solution.

**NFTFlex** is a user-friendly platform that enables users to display their Solana NFTs on social media with the following features:

1. **Social Media Embed**: Automatically generates a summary card with a large image and the owner's Twitter handle using a simple URL like `showoff.me/:mint-address`.

2. **Cardinal Twitter Integration**: Displays the correct Twitter handle of the NFT owner, making it easy for users to show off their NFTs and build their online presence.

3. **NFT Showcasing**: Empowers NFT owners to showcase their assets on social media platforms with full ownership details, enhancing NFT adoption.

---

## ⚙️ Architecture.

![NFTFlex Architecture](./)
[Excalidraw File](./)

---

## 🛠 Tools, Languages & Frameworks used.

- **ReactJS**: Frontend library for building interactive user interfaces.
- **Cardinal**: Integration for Twitter handle display linked with Solana wallets.
- **Node.js**: Backend runtime environment for server-side JavaScript.
- **Express.js**: Web framework for building RESTful APIs.
- **Solana Web3.js**: JavaScript library to interact with the Solana blockchain.
- **IPFS**: Decentralized storage for NFT metadata like images and descriptions.
- **Solana**: Blockchain to support NFT transactions and ownership data.

---

## 📂 Folder Structure.

- **client**: Contains the frontend codebase.
- **server**: Contains the backend code and API integrations.

---

## 🧑‍💻 Contributions to this repo are WELCOME.👋

- 🎨 Any improvements to the design and UI are welcome.
- 🔨 Try to break the website by testing it to find any bugs. If you find any, check if there is an issue already open for it, if there is none, then report it.

---

## 🔃 Steps to be followed in order to make valid contributions to this repo.

**1.** Fork the [NFTFlex](https://github.com/mrinnnmoy/NFTFlex) repo by clicking on the fork button on the top of the page. This will create a copy of this repository in your account.

**2.** Clone the forked repository

        git clone "https://github.com/<your-github-username>/NFTFlex"

- Download and install Node JS v16.16.0
- Download and install Git.
- Go to the terminal of your code editor and run "npm install" to download packages.
- Run "npm run dev" to start a local server.

**3.** Make necessary changes and commit those changes. <br />
Remember never push anything to the Main branch. <br />

Always change your branch to "develop" using:

    git checkout develop

Again check your current branch using:

    git branch

It should point \*develop

Now add your changes using:

    git add files-you-edited

If there are multiple files you can use:

    git add .

Now create a commit message using:

    git commit -m "<commit-message-goes-here>"

**4.** Push changes to GitHub

    git push origin develop

**5.** Create a Pull Request 👋<br>

Now you go to your repository on GitHub, you’ll see a `Compare & pull request` button. Click on that button and now write a summary of what changes you have done. (Attach images if required). I will review your code and merge it if it passes all the tests.❤️
