Install React from Terminal
     -npm install -g create-react-app
     -create-react-app --version
     -create-react-app <project_name>
To Run the development server
    -npm start


First Program to print "Sheetal Tyagi"
     -const root=ReactDOM.createRoot(document.getElementById('root'));
     -root.render(<h1>Sheetal Tyagi</h1>);

Their are two main Libraries do we have to use to make a React applictions
1.React
2.ReactDOM

ReactL Library has two things
1.createElement()
2.render()

Creating an HTML element : createElement()
Step 1-Create a React element/javascript object
     For example-const result=React.createElement();
Step 2-Pass the arguments to the function
     For example-const result=React.createElement('h1',{id:'abc'},'This is heading first');

Creating a HTML element : render()
It is used to render and display the react element on the web pages.
For example-const result=React.createElement('h1',{id:'abc'},'This is heading first');
            ReactDom.render(result,document.getElementById('react-container')

JSX-It is an extension to the JS that is used with React to create HTML elements.
     

