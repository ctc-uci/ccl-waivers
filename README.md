# Child Creativity Lab - Waivers
![CCL Logo](https://user-images.githubusercontent.com/45449494/130186262-a0855101-be2f-4cf2-a9fd-2c7ea289b115.png)
#### Child Creativity Lab aims to foster the next generation of critical thinkers, innovators, and leaders through hands-on creativity enhancing exploration. They incorporate creativity into STEM education, making it easier for children to understand and enjoy.

**🌐** [Website](https://childcreativitylab.org) | [Twitter](https://twitter.com/childcreativity) | [Facebook](https://www.facebook.com/childcreativitylab/) | [Instagram](https://www.instagram.com/childcreativitylab/) | [YouTube](https://www.youtube.com/channel/UCgMSq7Xy2oXarbaUBO2cQIA)


![CCL Web Preview](https://user-images.githubusercontent.com/45449494/130186401-0a6fde21-0def-4922-a209-f245d5d2a258.png)


## 🔎 About the Project

*Child Creativity Lab physically scans event and workshop paper waivers for uploading to an online drive, which is a time-consuming and error-prone process.*


🆙 We created an online waiver management system where volunteers and participants can sign waivers automatically stored on a dashboard for admins to access. This solution will reduce paper usage and improve waiver organization for Child Creativity Lab's workshops and other activities.

![Waivers Home](https://user-images.githubusercontent.com/45449494/130186434-b2bbc0be-ce5b-48ae-aab5-9d2a6840cfdb.png)
![Waivers Upload](https://user-images.githubusercontent.com/45449494/130186442-b6fb3d01-7fe2-4de3-b465-99dbe69afe34.png)



**Tech Stack:**

**🔼 Frontend:** React

**🔽 Backend:** NodeJS + MySQL


## 💻 Development 

### 🔨 Getting Set Up

1. **Clone the project.**
	
	The `--recursive` flag will download both the frontend and backend submodule repos.  

    `git clone --recursive git@github.com:ctc-uci/ccl-waivers.git`

2. **Install the dependencies.**

	A postinstall script will also run to install dependencies in the submodules.

	`npm install`

3. **Add the `.env` file to `ccl-waivers-backend`.**


### 💨 Running the Project

- `npm start` will run the frontend and backend concurrently
- To start the frontend or backend separately, `cd` into its respective directory and use `npm start` there.
