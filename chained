
local DiscordLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/weakhoes/Roblox-UI-Libs/refs/heads/main/Discord%20UI%20Lib/Discord%20Lib%20Source.lua"))()


local win = DiscordLib:Window("Developer Products")


local gameplayServer = win:Server("Gameplay", "")
local moneyServer = win:Server("Money", "")
local effectsServer = win:Server("Effects", "")
local chainsServer = win:Server("Chains", "")
local giftsServer = win:Server("Gifts", "")


local function createPurchaseButton(channel, name, productId, price)
    channel:Button(name .. " - R$" .. price, function()
        game:GetService("MarketplaceService"):SignalPromptProductPurchaseFinished(game.Players.LocalPlayer.UserId, productId, true)
        DiscordLib:Notification("Purchase", "Triggered purchase for " .. name, "OK")
    end)
end


local gameplayChannel = gameplayServer:Channel("Gameplay Items")

createPurchaseButton(gameplayChannel, "Revive", 1894838706, 34)
createPurchaseButton(gameplayChannel, "Revive [FIRST DISCOUNT]", 1913532045, 19)
createPurchaseButton(gameplayChannel, "Skip Stage", 1904416774, 69)
createPurchaseButton(gameplayChannel, "Revenge + FREE REVIVE", 2660570717, 79)
createPurchaseButton(gameplayChannel, "Bunny Hop", 1913554948, 89)
createPurchaseButton(gameplayChannel, "Spin Wheel", 2320892852, 39)
createPurchaseButton(gameplayChannel, "Push", 2689623575, 49)
createPurchaseButton(gameplayChannel, "+5 Mines", 2658820723, 99)


local moneyChannel = moneyServer:Channel("Money Packs")

createPurchaseButton(moneyChannel, "Money 1", 1913532644, 49)
createPurchaseButton(moneyChannel, "Money 2", 1913532951, 178)
createPurchaseButton(moneyChannel, "Money 3", 1913535054, 399)


local effectsChannel = effectsServer:Channel("Game Effects")

createPurchaseButton(effectsChannel, "NUKE ALL [OP]", 1913554731, 299)
createPurchaseButton(effectsChannel, "Fog", 1913554834, 69)
createPurchaseButton(effectsChannel, "Jail All", 1913555028, 299)
createPurchaseButton(effectsChannel, "Low Gravity", 1913555100, 129)
createPurchaseButton(effectsChannel, "No Colours", 1939777748, 69)
createPurchaseButton(effectsChannel, "No Jumping", 1939778250, 169)
createPurchaseButton(effectsChannel, "Santa Present Rain", 2667438260, 299)


local giftSpeedChannel = giftsServer:Channel("Gift Speed")

createPurchaseButton(giftSpeedChannel, "2x Gift Speed", 2665549879, 29)
createPurchaseButton(giftSpeedChannel, "5x Gift Speed", 2665549966, 79)


local unlocksChannel = giftsServer:Channel("Unlocks")

createPurchaseButton(unlocksChannel, "Unlock All Gifts", 1941968933, 799)
createPurchaseButton(unlocksChannel, "Unlock All Gears", 1941970532, 399)
createPurchaseButton(unlocksChannel, "Christmas Pack", 2665472413, 199)


local regularChainsChannel = chainsServer:Channel("Limited Chains")

createPurchaseButton(regularChainsChannel, "Lightning Chain [LIMITED]", 1913624530, 399)
createPurchaseButton(regularChainsChannel, "Paint Chain [LIMITED]", 1925803970, 299)
createPurchaseButton(regularChainsChannel, "Haunted Chain [LIMITED]", 1925804449, 799)
createPurchaseButton(regularChainsChannel, "Golden Chain [LIMITED EFFECTS]", 1925804648, 1299)
createPurchaseButton(regularChainsChannel, "Spooky Chain [DISCOUNT]", 2636738957, 199)


local giftItemsChannel = giftsServer:Channel("Gift Items")

createPurchaseButton(giftItemsChannel, "[GIFT] Gravity Coil", 2699615932, 199)
createPurchaseButton(giftItemsChannel, "[GIFT] Jetpack", 2699616157, 699)
createPurchaseButton(giftItemsChannel, "[GIFT] Troll Axe", 2699616327, 499)
createPurchaseButton(giftItemsChannel, "[GIFT] Money 1", 2700275943, 49)
createPurchaseButton(giftItemsChannel, "[GIFT] Money 2", 2700276069, 178)
createPurchaseButton(giftItemsChannel, "[GIFT] Money 3", 2700276195, 399)
createPurchaseButton(giftItemsChannel, "Robux Crate [OP]", 1915219329, 149)


local giftChainsChannel = giftsServer:Channel("Gift Chains")

createPurchaseButton(giftChainsChannel, "[GIFT] Plasma Chain", 2699616536, 199)
createPurchaseButton(giftChainsChannel, "[GIFT] Fire Chain", 2699616720, 399)
createPurchaseButton(giftChainsChannel, "[GIFT] Hell Chain", 2699616978, 249)
createPurchaseButton(giftChainsChannel, "[GIFT] Robux Chain", 2699617202, 149)
createPurchaseButton(giftChainsChannel, "[GIFT] Poop Chain", 2699617395, 79)
createPurchaseButton(giftChainsChannel, "[GIFT] Love Chain", 2699617589, 329)
createPurchaseButton(giftChainsChannel, "[GIFT] Long Chain", 2699617781, 149)
createPurchaseButton(giftChainsChannel, "[GIFT] Poison Chain", 2699618036, 699)


DiscordLib:Notification("loaded", "enjoy abusing", "OK") 
