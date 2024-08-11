# Viewtiful

## Description

🍿 Wiki site that provides movie information, 2024.04~2024.06

## Member

+ [Sangyoon Lee](https://github.com/so-so2456) [Leader, Front-end]
+ Hyunwook Ryu [Front-end]
+ [Moonsoo Park](https://github.com/m0onsoo)  [Back-end]
+ Mincheol Jeong [Back-end]

## Function

1. Search for the movie title and display information about the movie.
2. It shows the top 3 popular movies, and clicking on it will show information about the movie.
3. Movie information includes title, poster, rating, genre, release date, overview, and review.

## Screen

![image](https://github.com/so-so2456/Viewtiful/assets/65073648/c8e05598-3ade-415f-9b99-e6c1b9829c7f)
<img width="452" alt="image" src="https://github.com/so-so2456/Viewtiful/assets/65073648/d8f677a0-1bd2-4374-95eb-b6c1e215fa0c">
![image](https://github.com/so-so2456/Viewtiful/assets/65073648/88853935-0364-4209-a0dd-3cfcf3769b8a)

## Language

Front-end uses Svelte (JS-based)

![image](https://github.com/so-so2456/Viewtiful/assets/65073648/12ae2f0b-275b-476c-bf0a-6040d4bb10d8)

No Virtual Dom!! 🫢

Svelt changes all code to vanilla js at build time, not execution time.

---

Backend uses FastAPI (python-based)

![image](https://github.com/so-so2456/Viewtiful/assets/65073648/8c852446-3f0a-4725-977e-ebd1a2f8fd36)

FastAPI >> Flask (Good performance and easy to create, so 
“Fast” API)

Automatic documentation, including Swagger UI ("{url}/docs")

## Deployment

Heroku(backend) & Vercel(frontend)

[Viewtiful](https://viewtiful-eta.vercel.app)

## Dependency

```
// frontend
$ npm --version
10.1.0

"devDependencies": {
  "@rollup/plugin-commonjs": "^24.0.0",
  "@rollup/plugin-node-resolve": "^15.0.0",
  "@rollup/plugin-replace": "^5.0.7",
  "@rollup/plugin-terser": "^0.4.0",
  "dotenv": "^16.4.5",
  "rollup": "^3.15.0",
  "rollup-plugin-css-only": "^4.3.0",
  "rollup-plugin-livereload": "^2.0.0",
  "rollup-plugin-svelte": "^7.1.2",
  "svelte": "^3.55.0"
},
"dependencies": {
  "sirv-cli": "^2.0.0"
}


// backend
python = "^3.12"
fastapi = "^0.111.0"
uvicorn = "^0.29.0"
jinja2 = "^3.1.4"
aiofiles = "^23.2.1"
python-dotenv = "^1.0.1"
httpx = "^0.27.0"
```

## Command

```
$ git clone https://github.com/so-so2456/Viewtiful.git
$ cd Viewtiful
```

Frontend

**(you should install npm!!)**

```
$ cd frontend
$ npm install
$ npm run dev
```

Backend

**(you should install python!!)**

```
$ cd backend
$ pip install -r requirements.txt
$ uvicorn main:app --reload
```

## Reference

[TMDB](https://www.themoviedb.org/)
</div>
