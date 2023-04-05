# EarWax
EarWax GUI Library for Roblox
by ZuxTheTank 

How to use:
(See example)

library = loadstring(game:HttpGet("https://raw.githubusercontent.com/ZuxTheTank/EarWax/main/EarWax"))() 

library.New(table[strng index = value] options) -> Window
		* Used to create a new Window 
    
Window:Log(table[string] text, Color3 color) -> nil
		* Used for writing text into the gui 
		* Function also used for type hinting commands
    
Window:ClearLog() -> nil 
		* Used for clearing the logs
		* Logs will auto clear whenever user types
    
Window:NewCommand(string name) ->
		table
		[
			Command:Add(string name, function callback) -> nil
			  * Used for making a command
			Command:Delete(string name) -> nil
				* Used for deleting a command
		]
		* Used to create a new command
