# FlexBox-flex-direction
## flex, inline-flex. flex-direction: column y row
```javascript
.contenedor-flex {
    display: flex;
    border: 3px solid black; 
    /** Direcciones row y row-reverse**/
    flex-direction: row;/* una vez que se declara display:flex por defecto flex-direction:row*/
}
.contenedor-inline-flex {
    display: inline-flex;
    border: 3px solid black; 
    /** Direcciones row y row-reverse**/
    flex-direction: row;
}

.contenedor-flexcolumn {
    display: flex;
    border: 3px solid black; 
    /** Direcciones column y column-reverse**/
    flex-direction: column;
}
.contenedor-inline-flex-column {
    display: inline-flex;
    border: 3px solid black; 
  /** Direcciones column y column-reverse**/
    flex-direction: column;
}
```
