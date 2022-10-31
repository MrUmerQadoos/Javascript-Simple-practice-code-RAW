# Javascript-Simple-practice-code-RAW
This code just use function , array with advance methods for practicing 

// // const actors = [
// //     {
// //         name:'actor1',
// //         payment:900
// //     },
// //     {
// //         name:'actor1',
// //         payment:100
// //     }, {
// //         name:'actor1',
// //         payment:20
// //     }
// ]

// -------For Loop_------

// for(let i=0; i<actors.length; i++){
 
//     actors[i].payment = actors[i].payment-10;

// --------------forEach loop ------------

// actors.forEach((actor)=>
// actor.payment=actor.payment - 10
// )

// console.log(actors)

// --------FILTER-------

// const students = [
//     {
//         name:'Ali',
//         mark:35
//     },
//     {
//         name:'Umer',
//         mark:90,
//     },
//     {
//         name:'baber',
//         mark:40,
//     }
// ]


// const fail = students.filter((student)=> student.mark<45)



// const fail = students.filter((student)=>{

//     if(student.mark < 45 )
//     {
//         return true;
//     // console.log("PASS")
//     }
//     else{
//         return false;
//     }
// }

// );
// console.log(fail);

// _________MAP________

// const Users = [
//     {
//         fname:'Umer',
//         lname:'Qadoos'
//     },
//     {
//         fname:'Haris',
//         lname:'Qadoos'
//     }
// ]

// const FinalUser = Users.map((user)=>{
//         return{
//             FullName:`${user.fname} ${user.lname}`
//         };
//     });
// console.log(FinalUser)

                                            //_________________REDUCE__________________________-

// const movies = [

// {
//     name:'Movie 1',
//     budget:100
// },
// {
//     name:'Movie2',
//     budget:240
// },
// {
//     name:'Movie3',
//     budget:450
// }
// ]
//  const total = movies.reduce((acc,movie)=>{
//     acc=acc+movie.budget;
//     return acc;


// },0)
// console.log(total)

                                        // _____________CALL BACK FUNCTION_______________
// function a(text,formatcb){
//     return typeof formatcb === 'function' ? formatcb(text):text.toUpperCase();
// }
// const result = a('hello',function(text){
// return text.charAt(0).toUpperCase() + text.slice(1)
// })
// console.log(result)


