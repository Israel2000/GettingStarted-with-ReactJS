## THE SETUP
 add this into index.html
 ```
<script src="https://unpkg.com/react@16/umd/react.development.js"></script> <br/> 
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>   </br>
<script src="https://unpkg.com/babel-standalone@6.15.0/babel.min.js"></script>  
 ```
```
    <div id="root"></div>  
    <script type="text/babel">  
      
    /*   
    ADD REACT CODE HERE 
    */  
      
    </script>  
```

## COMPONENTS
class Hello extends React.Component {
    render() {
        return <h1>Hello world!</h1>
    }
}