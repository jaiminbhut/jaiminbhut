# Jaimin Bhut

Full-stack and mobile tech lead. I build iOS and Android apps from an empty repo, the Angular web front end and the .NET API behind them, and the pipeline that ships all of it: Docker, AWS or on-prem servers, and database migrations run in production.

## Work you can check

- **[Doorlist](https://github.com/jaiminbhut/doorlist)** ([v1.0.0](https://github.com/jaiminbhut/doorlist/releases/tag/v1.0.0)): free event tickets with door check-in, built in the open as a reference project.
  - **Stack:** Angular, ASP.NET Core on .NET 10, EF Core and SQL Server, Docker and GitHub Actions.
  - **Tickets** are signed QR codes that the door can check offline, and browser tests run the whole flow on every pull request.
  - **Migrations:** CI checks every pull request's migrations against the API version on `main`, and [breaking schema changes ship in expand/contract steps](https://github.com/jaiminbhut/doorlist/blob/main/docs/migrations.md).
  - **Deploys:** the pipeline is rehearsed end to end, failure paths included.
- **[Flabs case study](https://devtownhall.com/work/flabs-healthcare-platform)**: four production React Native apps for a healthcare platform, serving about 10K users. I built them from scratch, moved them to Expo one app at a time, and set up CI/CD to the App Store and Google Play.
- **[Clip & Board](https://devtownhall.com/clipboard)**: a native macOS clipboard manager in Swift and SwiftUI, in public beta.
- **[Clarity](https://github.com/jaiminbhut/clarity)**: a speech companion app built with Expo.
- **Writing**: [Shipping a React Native app without guessing](https://devtownhall.com/writing/shipping-react-native-without-guessing), and [Moving four live React Native apps to Expo, one at a time](https://devtownhall.com/writing/moving-live-react-native-apps-to-expo).

## What I work in

- **Mobile:** React Native, Expo, TypeScript, Flutter
- **Web:** Angular, React
- **Backend:** .NET / ASP.NET Core, EF Core, SQL Server, Node.js
- **Shipping:** Docker, AWS, on-prem servers, GitHub Actions, EAS

## How I lead

I make the architecture decisions, review code and set the standards a team works to, and plan and estimate the work. Doorlist shows how I run a codebase in public: [architecture decision records](https://github.com/jaiminbhut/doorlist/tree/main/docs/adr), [contribution rules](https://github.com/jaiminbhut/doorlist/blob/main/CONTRIBUTING.md), pull requests with a checklist, and a milestone roadmap.

## Contact

[devtownhall.com](https://devtownhall.com) · [LinkedIn](https://www.linkedin.com/in/jaimin-bhut) · [Email](mailto:jaiminbhut35@gmail.com) · [X](https://x.com/jaiminbhut) · [Stack Overflow](https://stackoverflow.com/users/14816800/jaimin-bhut) · [Medium](https://medium.com/@jaiminbhut35) · [DEV](https://dev.to/jaiminbhut)
