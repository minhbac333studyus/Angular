# Angular

Array:
 let list: number = [1,2,3,4];
 let list Array<number> = [1,2,3,4];
 Tuble:
  let x: [string, number]
  x = ["hello",10];
  console.log(x[0].substr(1)) //oke
  console.log(x[1].substr(1)) //oke
 Enum:
  enum PrintMedia{
    Newspaper,Newsletter,Magazine=6,Book};
    //  Book in this case = 7
  Object
    var person ={ firstName:"john", lastName:"smith"};
    console.log(person.firstName)
    console.log(person.lastName)
   Union Type:
  var itemAvailable: boolean|number;
  function fisplayType(code: (string| number)){
    if(typeof code ==="number")
      console.log("code is number");
    else if( typeof(code) === "string")
      console.log("code is string");
   
  }
  Name function:
  function add( x: number , y: number):number{
     return x+ y ;
  }
  Anonymous Function :
   let myAdd = function(x: number, y : number): number{
      return x+ y;
  }
  
  
  Arrow function:
  var getName = () =>  "john Smith";
  console.log(getName());
  
  
  Rest parameter
  function getFullName(firstNmae: string, ...restOfName: string[]){
    return restOfName.join(" ");
  }
  
  Accessor get/set in class
  get getName(){
    return this.name;
  }
  set setName(value:string){
    this.name = value;
  }
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
