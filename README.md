<p align="center">
  <a>
    <img src="https://i.imgur.com/B1EZxsB.png" alt="Moltin React Demo Store" />
  </a>
</p>

## Development

```bash
git clone https://github.com/zhangwei5479/react-demo-store.git
cd react-demo-store
yarn # or npm install
yarn start # or npm start
```

Note: You will want to change the `client_id` inside `src/moltin.js` with your own moltin store credentials.

This demo store uses the Redux "[ducks](https://github.com/erikras/ducks-modular-redux)" approach to bundling reducers and actions.

## Deployment

### Heroku

![Deploy](https://www.herokucdn.com/deploy/button.png)

### Docker

1. [Download and install docker](https://docs.docker.com/engine/installation/)
2. Make sure docker is running locally
3. Run `docker build -t lamp .` at command line
4. Run the docker image with the command `docker run -p 5000 IMAGE_ID` where `IMAGE_ID` is the image ID shown in the result of step 3.
5. Access your app on port 5000

## Copyright and license

The MIT License (MIT). Please see License File for more information.
<p align="center"><img src="https://avatars3.githubusercontent.com/u/47307975?s=400&u=5d3a6ad302503c236b60f5d85a0e32d564898838&v=4" width="50" height="50"/></p>
<p align="center">
  <sub>A little project by <a href="https://github.com/zhangwei5479">Zhang Wei</a></sub>
</p>
</p>
