# mm2script
-- Script de Troca simples no Roblox Studio
local TradeButton = script.Parent -- Botão de "Troca" no jogo
local player = game.Players.LocalPlayer
local tradeOpen = false

-- Função que abre a interface de troca
local function openTradeInterface()
    -- Aqui você pode criar a interface de troca com as opções de itens
    print("Interface de troca aberta!")
    tradeOpen = true
end

-- Função que fecha a interface de troca
local function closeTradeInterface()
    -- Aqui você pode fechar a interface de troca
    print("Interface de troca fechada!")
    tradeOpen = false
end

-- Quando o jogador clicar
