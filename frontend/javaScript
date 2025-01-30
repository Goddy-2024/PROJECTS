//W3 SCHOOLS - JAVASCRIPT (TIME FUNCTION AND THE OBJECT MODEL)

/*var toDay = new Date('07/10/2005')
console.log(toDay)
console.log(toDay.valueOf())
console.log(toDay.getFullYear() - new Date().getFullYear())
var test = new Date(823230245000)

console.log(test)
//returning the day of the month of the date stated in test use .getDate()
console.log(test.getDate())
toDay.setMonth(9)
console.log(toDay)
*/

//JAVASCRIPT OBJECTS
/*
    const student = {};
    student.fname = "Godswill";
    student.lname = "Ajuoga";
    student.mname = "Omondi";
    console.log(student)*/

    //USING THE NEW KEYWORD
    /*const student = Object();
    student.fname = "Godswill";
    student.lname = "Ajuoga";
    student.mname = "Omondi";
    //adding properties
    student.regNo = "CIT-227-096/2024";
    student.hostNo = "D316";
    student.courseName = "Bsc Software Engineering";
    student.fullName = student.fname + " " + student.mname + " " + student.lname;
    
    console.log(student)


    console.log(student.mname)//accessing object properties
    console.log(student.courseName)
    console.log(student.fullName)*/
//JAVASCRIPT OBJECT METHODS {FUNCTONS PERFORMED IN A JAJASCRIPT OBJECT}
    const student2 = {fname: "Godswill", 
                      lname: "Omondi", 
                      courseName : "Bsc in S/w Engineering",
                      regNo: "CIT-227-096/2024",
                      fullName: function(){
                    return this.fname + " " + this.lname;
                }
            };
                console.log(student2.fullName())
                    
                
                console.log(student2.lname.length)//accessing the length of a property
                delete(student2.courseName) // deletes the property courseName from the student2 object
                console.log(student2)
//NESTED OBJECTS
                student2.courseName = "Bsc S.Engineering"
student2.academia = {
    primary: "Kisumu", secondary: "Maseno", tertiary: "Multimedia"
}
console.log(student2)
console.log(student2.academia.secondary)//accessing nested objects
document.getElementById('test2').innerHTML = "Full name: " + student2.fullName();
document.getElementById('bg').style.background = 'black';
document.getElementById('bg').style.color = 'white';

//DISPLAYING PROPERTIES: As a string

document.getElementById('test').innerHTML = student2.regNo + " " + student2.academia.tertiary + " " + student2.courseName ;

//Using Object.values() - returns an array of data from the objects
delete(student2.fullName)
delete(student2.academia)
//Create an array named myStudent first
//Assign it to contain the values of the Student2 Object
const myStudent = Object.values(student2)
console.log(myStudent)

document.getElementById('test').innerHTML = myStudent


