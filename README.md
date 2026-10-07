# apartment-list

This repository contains my work for a job interview with **Apartment List**.

## About Apartment List

[Apartment List](https://www.apartmentlist.com) is an online rental marketplace, founded in 2011 and based in San Francisco. Instead of making renters scroll through endless listings, it asks about their preferences and budget, then recommends apartments that fit. Property managers use it to reach qualified renters. The company also publishes rental market research, including its National Rent Report.

**Mission:** Build a better world of renting for everyone by removing the pain and complexity and making renting more personal and flexible.

### Values

- **Go Beyond:** Show up every day as dedicated, innovative thinkers so renters and clients get what they want and deserve.
- **Always Home:** Be available around the clock with an experience that feels like home.
- **Check All The Boxes:** Deliver curated properties that match each renter's wishlist.
- **Your Silver Lining:** Take care of the tedious parts of the search so renters can enjoy finding their next home.
- **Do Better:** Hold a high bar for renting and deliver on it with every move-in.

## Build & Run

A Spring Boot 4 web app. Requires JDK 25. Uses the Gradle wrapper, so no local Gradle install is needed.

```sh
./gradlew build     # compile and run tests
./gradlew test      # run tests only
./gradlew bootRun   # start the server on http://localhost:8080
```

Check that the server is up:

```sh
curl http://localhost:8080/health
# {"status":"ok"}
```

Sample requests are in `requests.http` (runnable from IntelliJ).
