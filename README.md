## EMMA SONG

import React from 'react'
export default class App extends React.Component {
constructor0)
{
super)
this.state = {
count: 0
}
this.handleClick = this.handleClick.bind(this)
}
handleClick() {
this.setState(prestate = {
return {
count: preState.count + 1
}
7)
}
render0 f
return <div>
<h1>{this.state.count}</h1>
<button onClick={this.handleClick}>Change!</button>
<div>
