# Watch This Next

## Project Description

A full-stack movie review application based on the freeCodeCamp tutorial.
This project was developed following freeCodeCamp’s course on full-stack development, which features MongoDB for the database, Java and Spring Boot for the backend, and React for the frontend.

[Frontend Respository](https://github.com/hynwkm/movies-client)

## Installation

1. Clone the repository
2. cd project-directory-name
3. npm install
4. npm run dev

## API Endpoints

#### **Get All Users**
- **Method:** GET
- **EndPoint:** /api/v1/movies
- **Description:** Gets list of all available movies
- **Response:**
  - **Status Code:** 200 OK
  - **Response Body:**
    ``` json
    [
      {
        "id": {
            "timestamp": 1723515876,
            "date": "2024-08-13T02:24:36.000+00:00"
        },
        "imdbId": "tt3915174",
        "title": "Puss in Boots: The Last Wish",
        "releaseDate": "2022-12-21",
        "trailerLink": "https://www.youtube.com/watch?v=tHb7WlgyaUc",
        "poster": "https://image.tmdb.org/t/p/w500/1NqwE6LP9IEdOZ57NCT51ftHtWT.jpg",
        "genres": [
            "Animation",
            "Action",
            "Adventure",
            "Comedy",
            "Family"
        ],
        "backdrops": [
            "https://image.tmdb.org/t/p/original/r9PkFnRUIthgBp2JZZzD380MWZy.jpg",
            "https://image.tmdb.org/t/p/original/faXT8V80JRhnArTAeYXz0Eutpv9.jpg",
            "https://image.tmdb.org/t/p/original/pdrlEaknhta2wvE2dcD8XDEbAI4.jpg",
            "https://image.tmdb.org/t/p/original/tGwO4xcBjhXC0p5qlkw37TrH6S6.jpg",
            "https://image.tmdb.org/t/p/original/cP8YNG3XUeBmO8Jk7Skzq3vwHy1.jpg",
            "https://image.tmdb.org/t/p/original/qLE8yuieTDN93WNJRmFSAEJChOg.jpg",
            "https://image.tmdb.org/t/p/original/vNuHqmOJRQXY0PBd887DklSDlBP.jpg",
            "https://image.tmdb.org/t/p/original/uUCc62M0I3lpZy0SiydbBmUIpNi.jpg",
            "https://image.tmdb.org/t/p/original/2wPJIFrBhzzAP8oHDOlShMkERH6.jpg",
            "https://image.tmdb.org/t/p/original/fnfirCEDIkxZnQEtEMMSgllm0KZ.jpg"
        ],
        "reviewIds": [
            {
                "id": "66c53a9d1897566bcb1f98dc",
                "body": "Yeah"
            },
            {
                "id": "66c53af01897566bcb1f98dd",
                "body": "Yeah"
            },
            {
                "id": "66c53b2b1897566bcb1f98de",
                "body": "Yeah"
            },
            {
                "id": "66c53de11897566bcb1f98e0",
                "body": "efw"
            },
            {
                "id": "66c53deb1897566bcb1f98e1",
                "body": "wefwfw"
            },
            {
                "id": "66c55c641897566bcb1f98e6",
                "body": "cool"
            },
            {
                "id": "66c55c801897566bcb1f98e7",
                "body": "awesome"
            },
            {
                "id": "66c55c9f1897566bcb1f98e8",
                "body": "cool"
            },
            {
                "id": "66c55d711897566bcb1f98e9",
                "body": "nice"
            }
        ]
      },
    ]
    ```

## Contact

Created by [Hyun Woo Kim](https://hynwkm.github.io/)
[LinkedIn](https://www.linkedin.com/in/hyunwoo-kim/)
