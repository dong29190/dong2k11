getgenv().Config = {
  ["Hide"] = true,
  ["WhiteScreen"] = false, 
  ["Fps Boost"] = true,
  ["Webhook"] =   ["Team"] = "Pirates", 
  ["Fps Cap"] = 30,
  ["Item"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0.3},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["C"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Blox Fruit"] = {
            ["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0.4},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["C"] = {["Enable"] = true, ["Hold Time"] = 0.1},
            ["V"] = {["Enable"] = false, ["Hold Time"] = 0},
            ["F"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Sword"] = {
            ["Enable"] = false,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Gun"] = {
            ["Enable"] = false,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0}
        } 
      } 
}

loadstring(game:HttpGet("https://eltrul.xyz/Annie Bounty.lua"))()
