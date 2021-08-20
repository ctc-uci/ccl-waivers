# Child Creativity Lab - Waivers
[Banner placeholder]
#### Child Creativity Lab aims to foster the next generation of critical thinkers, innovators, and leaders through hands-on creativity enhancing exploration. They incorporate creativity in STEM education, making it easier for children to understand and enjoy.

**🌐** [Website](https://childcreativitylab.org) | [Twitter](https://twitter.com/childcreativity) | [Facebook](https://www.facebook.com/childcreativitylab/) | [Instagram](https://www.instagram.com/childcreativitylab/) | [YouTube](https://www.youtube.com/channel/UCgMSq7Xy2oXarbaUBO2cQIA)


[Screenshot of homepage]

## 🔎 About the Project

*Child Creativity Lab physically scans event and workshop paper waivers for uploading to an online drive, which is a time-consuming and error-prone process.*


🆙 We created an online waiver management system where volunteers and participants can sign waivers automatically stored in a dashboard for admins to access. This solution will reduce paper usage and improve waiver organization for Child Creativity Lab's workshops and other activities.

[screenshots]


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
