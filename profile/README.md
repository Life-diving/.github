<p align="center">
  <img src="logo.png" alt="Life Diving" width="120">
</p>

<h1 align="center">Life Diving</h1>

<p align="center">
  A psychology school: courses, a subscription-based club and psychological diagnostics.
</p>

## Repositories

- [`backend`](https://github.com/life-diving/backend): REST API built with Spring Boot on AWS Lambda, DynamoDB and Cognito. Courses, club subscriptions, WayForPay payments and psychological diagnostics
- [`life-diving-cognito-triggers`](https://github.com/life-diving/life-diving-cognito-triggers): AWS Lambda triggers for the Cognito User Pool: account linking on sign-up, default role and registration subscription after confirmation, branded auth emails
- [`life-diving-scheduled-jobs`](https://github.com/life-diving/life-diving-scheduled-jobs): AWS Lambda jobs around the backend's data: a daily sweep of failed WayForPay recurring-payment removals and a nudge that sends queued emails right away

## Links

- Website: https://life-diving.com
