
# React Widget

Useful widgets built to demonstrate tract capabilities

[Live React Widget](https://josephse91.github.io/React_widget/ "React Widget")




## Technologies Used

- Javascript
- React
- CSS


## Highlighted Features

**Lifecycle Usage**

While building components such as the clock component, using the lifecycle `componentDidMount()` is required to recursively rerender the current time by the second

```
 componentDidMount() {
    this.intervalId = setInterval(this.tick, 1000);
  }

  componentWillUnmount() {
    clearInterval(this.intervalId);
  }

  tick() {
    this.setState({time: new Date()});
  }
```

**More features**

Incorporate an API into a component

Managed asynchronous XMLHttpRequests to gather data





## Run Locally

Clone the project

```bash
git clone https://github.com/josephse91/React_widget.git
```

Go to the project directory

Install dependencies

`NOTE`: This app was created using npm version v14. To avoid conflict, it would be beneficial to install npm version 14.

```bash
  npm install
```

