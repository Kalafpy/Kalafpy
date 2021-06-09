-------------HOW TO MAKE A WORKING SHOP GUI IN ROBLOX STUDIO-------------

1: ADD A SCREEN GUI INSIDE "StarterGui"
2: INSERT A FRAME INSIDE "ScreenGui" THEN, CUSTOMIZE IT
3: RENAME THE SCREEN GUI TO "Shop"
4: GET RID OF THE OUTLINE IN "Frame"
5: ADD A TEXT LABEL INSIDE THE "Frame"
6: GET RID OF THE BACKROUND IN THE "TextLabel"
7: MAKE THE TEXT BIGGER BY CLICKING "Text Scaled"
8: CUSTOMIZE THE TEXT TO "Shop"
9: CHANGE THE FONT HOWEVER YOU LIKE IT AND CHANGE THE COLOR AS WELL
10: RENAME THE TEXT LABEL TO "Title"
11: INSERT A TEXT BUTTON INSIDE THE "Frame"
12: MAKE THE SIZE A BIT SMALLER, THE TEXT BUTTON WILL BE THE "X" TO CLOSE THE SHOP
13: CUSTOMIZE IT, AND GET RID OF THE OUTLINE
14: MAKE THE TEXT "X", MAKE IT TEXT SCALED AND MAKE THE TEXT COLOR WHITE, JUST LIKE EVERY GAME
15: RENAME THE TEXT BUTTON TO "Close"
16: ADD ANOTHER BUTTON, BUT MAKE SURE IT'S INSIDE "ScreenGui" / "Shop" AND IT WILL BE THE OPEN SHOP BUTTON
17: CUSTOMIZE IT, GET RID OF THE OUTLINE, MAKE THE TEXT SCALED, AND MAKE THE TEXT "Open Shop" OR ANYTHING YOU WANT
18: RENAME THE OPEN BUTTON "Open"
19: ADD A "Local Script" INSIDE "Open" BUTTON
20: GET RID OF "print("Hello world")" AND CHANGE IT TO THE SCRIPT I LEFT ON NUMBER 21'
21: -------------OPEN SHOP SCRIPT-------------
    script.Parent.MouseButton1Down:Connect(function()
       script.Parent.Parent.Frame.Visible = true
    end)
    
    ^                                        ^
    |                                        |
    |                                        |
    |                COPY IT                 |
    __________________________________________
    
    22: EXIT THE LOCAL SCRIPT AND CLICK "Frame" AND MAKE SURE IT'S NOT VISIBLE
    23: CLICK THE "Close" BUTTON AND INSERT A "Local Script"
    24: GET RID OF "print("Hello world")" AND CHANGE IT TO THE SCRIPT I LEFT ON NUMBER 25
    25: -------------OPEN SHOP SCRIPT-------------
    script.Parent.MouseButton1Down:Connect(function()
       script.Parent.Parent.Frame.Visible = false
    end)
    
    ^                                        ^
    |                                        |
    |                                        |
    |                COPY IT                 |
    __________________________________________
    
    I WILL ADD MORE DETAILS SOON BECAUSE I'M TOO LAZY RN LOL
    I HOPE THIS WORKED FOR YE!
    GO TEST THE GAME, IF THERES ANYTHING WRONG, FOLLOW MY STEPS!
    1) SEND ME A FRIEND REQUEST, HERE IS THE LINK: https://www.roblox.com/users/2585729483/profile
    2) BEFORE YOU DO THAT, MAKE SURE YOUR "About" HAS THIS DESCRIPTION -> I need help with the scripting please!
    3) I WILL CHECK YOUR PROFILE WHEN I'M ONLINE IF YOU NEEDED HELP WITH IT
    
    THANKS FOR USING THIS SCRIPT!
