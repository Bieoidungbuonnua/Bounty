getgenv().Setting = {

  ["Team"] = "Pirates",

  ["Chat"] = {},

  ["Skip Race V4"] = true,

  ["Misc"] = {

    ["Enable Lock Bounty"] = false,

    ["Lock Bounty"] = {0, 300000000},

    ["Hide Health"] = {4500,5000},

    ["Lock Camera"] = true,

    ["Enable Cam Farm"] = false,

    ["White Screen"] = false, 

    ["FPS Boost"] = false,

    ["Bypass TP"] = true, 

    ["Random & Store Fruit"] = true

  },

  ["Item"] = {

    ["Melee"] = {["Enable"] = true,

      ["Z"] = {["Enable"] = true, ["Hold Time"] = 1.5},

      ["X"] = {["Enable"] = true, ["Hold Time"] = 0.1},

      ["C"] = {["Enable"] = true, ["Hold Time"] = 0.1}

    },

    ["Blox Fruit"] = {["Disable"] = false,

      ["Z"] = {["Enable"] = true, ["Hold Time"] = 1.5},

      ["X"] = {["Enable"] = true, ["Hold Time"] = 0},

      ["C"] = {["Enable"] = true, ["Hold Time"] = 0},

      ["V"] = {["Enable"] = true, ["Hold Time"] = 0},

      ["F"] = {["Enable"] = true, ["Hold Time"] = 0}

    },

    ["Sword"] = {["Disable"] = true,

      ["Z"] = {["Enable"] = true, ["Hold Time"] = 0.1},

      ["X"] = {["Enable"] = true, ["Hold Time"] = 0.1}

    },

    ["Gun"] = {["Enable"] = true,

      ["Z"] = {["Enable"] = true, ["Hold Time"] = 0.1},

      ["X"] = {["Enable"] = true, ["Hold Time"] = 0.1}

    } 

  } 

}

loadstring(game:HttpGet("https://raw.githubusercontent.com/daviduts1/rua-hub/main/auto%20bouty"))()
