
# Ironbuster API

This is an API of movies and bookings for the Ironbuster App.


# API Reference

## Movies

#### Get all movies

```http
  GET /movies
```

| Request Body   | Type     | Description                    |
| :------------- | :------- | :----------------------------- |
| `empty`        | `string` | Provides a list of all movies  |

#### Create movie

```http
  POST /movies/new
```

| Request Body   | Type     | Description                       |
| :------------- | :------- | :-------------------------------- |
| `JSON`         | `string` | Creates a new movie from a form   |

#### Get movie details

```http
  GET /movies/:id
```

| Request Body   | Type     | Description                       |
| :------------- | :------- | :-------------------------------- |
| `empty`        | `string` | Requires Id of movie to fetch     |

#### Edit movie

```http
  PUT /movies/:id
```

| Request Body | Type     | Description                       |
| :----------- | :------- | :-------------------------------- |
| `JSON`       | `string` | Requires Id of movie to fetch     |

#### Delete movie

```http
  DELETE /movies/:id
```

| Request Body | Type     | Description                       |
| :----------- | :------- | :-------------------------------- |
| `empty`      | `string` | Removes an Id specified movie     |

## Bookings

#### Get all bookings

```http
  GET /bookings
```

| Request Body   | Type     | Description                      |
| :------------- | :------- | :------------------------------- |
| `empty`        | `string` | Provides a list of all bookings  |

#### Create bookings

```http
  POST /bookings/new
```

| Request Body  | Type     | Description                          |
| :------------ | :------- | :----------------------------------- |
| `JSON`        | `string` | Creates a new bookings from a form   |

#### Get booking details

```http
  GET /bookings/:id
```

| Request Body | Type     | Description                       |
| :----------- | :------- | :-------------------------------- |
| `empty`      | `string` | Requires Id of booking to fetch   |

#### Edit booking

```http
  PUT /bookings/:id
```

| Request Body   | Type     | Description                       |
| :------------- | :------- | :-------------------------------- |
| `JSON`         | `string` | Requires Id of booking to fetch   |

#### Delete booking

```http
  DELETE /bookings/:id
```

| Request Body   | Type     | Description                       |
| :------------- | :------- | :-------------------------------- |
| `empty`        | `string` | Removes an Id specified booking   |