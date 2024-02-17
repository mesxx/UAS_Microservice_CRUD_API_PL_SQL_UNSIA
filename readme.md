# User Management API

## Group 11

- Anggota 1 </br>
  Nama: M. ICHSAN FAUZAN </br>
  NIM: 220401010153 </br>
  PIC: structure endpoint, structure file, config database, register, login, getAllUsers, custom middleware and custom logger management

- Anggota 2 </br>
  Nama: KEVIN SETIAWAN </br>
  NIM: 210401120004 </br>
  PIC: getUserById, update and delete

- Anggota 3 </br>
  Nama: LANANG RABBANI </br>
  NIM: 220401020022 </br>
  PIC: structure endpoint

- Anggota 4 </br>
  Nama: KRISTIAN BUDI KUSUMA </br>
  NIM: 210401010115 </br>
  PIC: structure endpoint

## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Create database postgresql

```bash
  api_uas_pps_1
```

Install dependencies

```bash
  pip install fastapi uvicorn sqlalchemy "python-jose[cryptography]" "passlib[bcrypt]"
```

Start the server

```bash
  uvicorn main:app --reload
```
