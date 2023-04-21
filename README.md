# Coreui_Event
Currently in AICTE Event/Activity Management happens manually. Such examples of activities that happen manually are Booking of meeting room/auditorium, communication 
to all the bureaus/members regarding meetings through email and SMS alerts, intimate canteen for refreshment/Lunch/dinner arrangements, update the information on AICTE social media like Facebook & Twitter page, Report generation, activity log checking etc. This manual process generally takes a lot of time to implement and can cause delay to the actual work. With the fast-growing network of AICTE, it needs to automate its process to provide ease to manual work. This can highly increase in economic growth of AICTE and manage all events very smoothly with all information to have directed to one single portal. Summary:  Due to manually management of Events AICTE faces a lot of challenges where they lose a lot of time to gather all the events together.

Create a common portal for all AICTE Event/Activity management would ease you their work and make the work process robust and flexible. This will ensure AICTE to have all events under one umbrella from where the management would be easy and comfortable.




### Installation

``` bash
$ npm install
```

or

``` bash
$ yarn install
```

### Basic usage

``` bash
# dev server with hot reload at http://localhost:3000
$ npm start 
```

or 

``` bash
# dev server with hot reload at http://localhost:3000
$ yarn start
```

Navigate to [http://localhost:3000](http://localhost:3000). The app will automatically reload if you change any of the source files.

#### Build

Run `build` to build the project. The build artifacts will be stored in the `build/` directory.

```bash
# build for production with minification
$ npm run build
```

or

```bash
# build for production with minification
$ yarn build
```

## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
Client

├── public/          # static files
│   └── index.html   # html template
│
├── src/             # project root
│   ├── assets/      # images, icons, etc.
│   ├── components/  # common components - header, footer, sidebar, etc.
│   ├── layouts/     # layout containers
│   ├── scss/        # scss styles
│   ├── views/       # application views
│   ├── _nav.js      # sidebar navigation config
│   ├── App.js
│   ├── ...
│   ├── index.js
│   ├── routes.js    # routes config
│   └── store.js     # template state example 
│
└── package.json
```

```
Client

├── db/               # Database connection 
│   └── conn.js       # MongoDB connection code
│
├── middleware/       #cookies implementation
│   └── authenticate.js   # User authentication
│
├── middleware/        #Models
│   └── committeeSchema.js   # Committee
│   └── eventSchema.js       # Event
│   └── menuSchema.js        # Menu
│   └── taskSchema.js        # Task
│   └── tokenSchema.js       # Token
│   └── transactionSchema.js  # Transaction
│   └── userSchema.js         # User
│
├── router/          #Include all routers
│   └── auth.js      # User  APIs
│   └── committee.js # Committee  APIs
│   └── event.js     # Event  APIs
│   └── menu.js      # Menu  APIs
│   └── payment.js   # Transaction  APIs
│   └── task.js      # Task  APIs
│
├── utils/           #Email Verification
│   └── sendEmail.js #Verify Email using SMTP
│
│── app.js      
│
└── package.json
```

