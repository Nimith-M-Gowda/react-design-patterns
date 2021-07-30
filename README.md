# React Interesting Stuffs

#### What is the necessity of importing react-dom ?.

JSX wont be able to read by browser without react-dom since it is not standard for browsers .

#### how elements are differed by react

syntax for element/functions is
{
type: Title,
props: {
color: 'red',
children: 'Hello, Title!'
}
}
If the type is string then children becomes a dom node. if type is function it pass props to get back the underlying elements until it gets a tree of dom node .

#### Role of babel in react

Babel acts as transpiler(one source code to another source code ) by converting JSX to js . and babel can execute given input source file to transpiled output file in browser .Babel requires configuration .Once the installation is complete, we create a configuration file called .babelrc in the root folder

- Ex : `<div/>` ----> React.createElement('div') , that is JSX to javascript this conversion will be done by babel
