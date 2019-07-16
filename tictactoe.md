var materials:[String]=["Rock","Paper","Scissors"]
var combinations:[[String]]=[["Draw","Human loses","Human wins"],["Human loses","Draw","Human wins"],["Human loses","Human wins","Draw"]]
let flag1 = Int.random(in:0...2)
let flag2 = Int.random(in:0...2)
let p1 = materials[flag1]
let p2 = materials[flag2]
print("Human: ",materials[flag1])
print("CPU: ",materials[flag2])
print(combinations[flag1][flag2])
