# Data Types

- String (any charactor or text that wrap in single or double quotes)
    - Examples
        - `"pizza"`
        - `'burger'`
       

- Number (any numerical character)
    - Examples
        - `80/-`
        - `40/-`
- Boolean (similar to yes or no, 0 or 1)
    - Examples (not required quotes)
        - `true`
        - `false`

## JSON (JavaScript Object Notation)   
object which has it properties( value holder) and it methods (functioning / process)  

Menu
- Item name   : Burger
- Price       : 40/-
- Available   : True

- makenotavailable()
   - available: false

- makeavailable()
   - available: true   

Example
```json
{
      "name"    : "pradeep kumar",
      "salary"  : 10000,
      "Student" : false,
      "bonus"   : null,
      "skills"  : ["java","office","photoshop"],
      "address" : [
              {"type":"home","location":"gorantla","pincode":522034},
              {"type":"work","location":"guntur","pincode":522002}

      ]
}
```