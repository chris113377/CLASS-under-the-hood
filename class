function userCreator (name, score) {
    let newUser = Object.create (myFunction);
    newUser.name = name;
    newUser.score = score;
    return newUser;
};

let myFunction = {
    increment: function(){this.score++},
    login: function(){console.log('You are loggedin')}
}

let user1 = userCreator('Bob', 12);
let user2 = userCreator('Sam', 27);

user1.increment();
