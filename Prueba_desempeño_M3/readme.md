
Event Management 🎉

📋 Description

This is a Single Page Application for managing events, featuring role-based authentication, protected routes, session persistence, and CRUD operations connected to a simulated database using json-server.

🧑‍💻 Coder Info

* Name: Esteban Orozco Osorio
* Clan: Linus
* Email: Esteban Orozco Osorio
* ID: 1036250867

🚀 How to Run the Project

1. Clone the repository:


git clone 


2. Install dependencies:


npm install


3. Run the project:

You can use Live Server or run it with Vite:


npm run dev


🧪 Routes

| View              | Path                              | Access    |
| ----------------- | --------------------------------- | --------- |
| Home              | /index.html                       | Public    |
| Register          | /register.html                    | Visitor   |
| Login             | /login.html                       | Public    |
| Dashboard         | /dashboard.html                   | Protected |
| Create Event      | /dashboard/events/create.html     | Admin     |
| Edit Event        | /dashboard/events/edit.html?id=ID | Admin     |
| Unauthorized Page | /not-found.html                   | Automatic |

👥 User Types

Admin

* Can create, edit, and delete events.
* Default user:

  * Username: admin
  * Password: admin123

Visitor

* Can register and log in.
* Can sign up for events if spots are available.

🧰 Tools Used

* HTML5 + CSS3
* JavaScript
* json-server
* Local Storage
* Git

📬 Contact

Questions or suggestions? Feel free to email me at *estebanorozcoosorio@gmail.com* 🚀