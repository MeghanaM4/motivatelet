# motivatelet
a bookmarklet to motivate you to study for your AP physics exams
[drag me into your bookmarks bar] (javascript:(function() {
    reminders = ["getting a 5 is easy, lock in", "your physics teacher didn't get grey hairs just for you to fail",
        "the only L you're gonna get is angular momentum", "study unit 6, rotational inertia isn't gonna derive itself",
        "you are NOT an F student", "show gauss who's boss. no 17th century old man is going to best you", 
        "induction who?", "at this point, you're too far in.", "home stretch man, you will not die because of capacitance",
        "if you had to linearize your physics skill it would be slope = awesomeness", 
        "experimental design procedure has nothing on your study habits. minimize that uncertainty."];
    var msgInd = Math.floor(Math.random() * (reminders.length - 1));
    console.log(msgInd + ": " + reminders[msgInd]);
    alert(reminders[msgInd]);
})();)
