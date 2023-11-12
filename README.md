# React-shop-cloudfront

This is frontend starter project for nodejs-aws mentoring program. It uses the following technologies:

- [Vite](https://vitejs.dev/) as a project bundler
- [React](https://beta.reactjs.org/) as a frontend framework
- [React-router-dom](https://reactrouterdotcom.fly.dev/) as a routing library
- [MUI](https://mui.com/) as a UI framework
- [React-query](https://react-query-v3.tanstack.com/) as a data fetching library
- [Formik](https://formik.org/) as a form library
- [Yup](https://github.com/jquense/yup) as a validation schema
- [Vitest](https://vitest.dev/) as a test runner
- [MSW](https://mswjs.io/) as an API mocking library
- [Eslint](https://eslint.org/) as a code linting tool
- [Prettier](https://prettier.io/) as a code formatting tool
- [TypeScript](https://www.typescriptlang.org/) as a type checking tool

## Available Scripts

### `start`

Starts the project in dev mode with mocked API on local environment.

### `build`

Builds the project for production in `dist` folder.

### `cdk:prepare`

Makes CDK bootstrap (preparation) to work with AWS resources

### `build:deploy`

Builds the project for production in `dist` folder, deploys/redeploys stack resources into AWS if changed, uploads static to S3 with CloudFront invalidation if changed

### `destroy`

Destroy stack resources into AWS, use with caution!

### `preview`

Starts the project in production mode on local environment.

### `test`, `test:ui`, `test:coverage`

Runs tests in console, in browser or with coverage.

### `lint`, `prettier`

Runs linting and formatting for all files in `src` folder.

# Links for cross-check

## Manual S3 URL
https://awsdevrss-nodejs-aws-shop-react.s3.amazonaws.com/index.html

## Manual CloudFront URL
https://dgqwekqmxp3gk.cloudfront.net

## CDK S3 URL
https://nodejs-aws-shop-react-awsdevrss.s3.eu-west-3.amazonaws.com/index.html

## CDK CloudFront URL
https://dyfk99rjrorkr.cloudfront.net/
