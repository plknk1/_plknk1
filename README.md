if game.PlaceId == 2753915549 then
    World1 = true
elseif game.PlaceId == 4442272183 then
    World2 = true
elseif game.PlaceId == 7449423635 then
    World3 = true
end

function CheckQuest() 
        MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value
        if World1 then
            if MyLevel == 1 or MyLevel <= 9 then
                Mon = "Bandit"
                LevelQuest = 1
                NameQuest = "BanditQuest1"
                NameMon = "Bandit"
                CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
                CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)
            elseif MyLevel == 10 or MyLevel <= 14 then
                Mon = "Monkey"
                LevelQuest = 1
                NameQuest = "JungleQuest"
                NameMon = "Monkey"
                CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
                CFrameMon = CFrame.new(-1448.51806640625, 67.85301208496094, 11.46579647064209)
            elseif MyLevel == 15 or MyLevel <= 29 then
                Mon = "Gorilla"
                LevelQuest = 2
                NameQuest = "JungleQuest"
                NameMon = "Gorilla"
                CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
                CFrameMon = CFrame.new(-1129.8836669921875, 40.46354675292969, -525.4237060546875)
            elseif MyLevel == 30 or MyLevel <= 39 then
                Mon = "Pirate"
                LevelQuest = 1
                NameQuest = "BuggyQuest1"
                NameMon = "Pirate"
                CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
                CFrameMon = CFrame.new(-1103.513427734375, 13.752052307128906, 3896.091064453125)
            elseif MyLevel == 40 or MyLevel <= 59 then
                Mon = "Brute"
                LevelQuest = 2
                NameQuest = "BuggyQuest1"
                NameMon = "Brute"
                CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
                CFrameMon = CFrame.new(-1140.083740234375, 14.809885025024414, 4322.92138671875)
            elseif MyLevel == 60 or MyLevel <= 74 then
                Mon = "Desert Bandit"
                LevelQuest = 1
                NameQuest = "DesertQuest"
                NameMon = "Desert Bandit"
                CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
                CFrameMon = CFrame.new(924.7998046875, 6.44867467880249, 4481.5859375)
            elseif MyLevel == 75 or MyLevel <= 89 then
                Mon = "Desert Officer"
                LevelQuest = 2
                NameQuest = "DesertQuest"
                NameMon = "Desert Officer"
                CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
                CFrameMon = CFrame.new(1608.2822265625, 8.614224433898926, 4371.00732421875)
            elseif MyLevel == 90 or MyLevel <= 99 then
                Mon = "Snow Bandit"
                LevelQuest = 1
                NameQuest = "SnowQuest"
                NameMon = "Snow Bandit"
                CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
                CFrameMon = CFrame.new(1354.347900390625, 87.27277374267578, -1393.946533203125)
            elseif MyLevel == 100 or MyLevel <= 119 then
                Mon = "Snowman"
                LevelQuest = 2
                NameQuest = "SnowQuest"
                NameMon = "Snowman"
                CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
                CFrameMon = CFrame.new(1201.6412353515625, 144.57958984375, -1550.0670166015625)
            elseif MyLevel == 120 or MyLevel <= 149 then
                Mon = "Chief Petty Officer"
                LevelQuest = 1
                NameQuest = "MarineQuest2"
                NameMon = "Chief Petty Officer"
                CFrameQuest = CFrame.new(-5039.58643, 27.3500385, 4324.68018, 0, 0, -1, 0, 1, 0, 1, 0, 0)
                CFrameMon = CFrame.new(-4881.23095703125, 22.65204429626465, 4273.75244140625)
            elseif MyLevel == 150 or MyLevel <= 174 then
                Mon = "Sky Bandit"
                LevelQuest = 1
                NameQuest = "SkyQuest"
                NameMon = "Sky Bandit"
                CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
                CFrameMon = CFrame.new(-4953.20703125, 295.74420166015625, -2899.22900390625)
            elseif MyLevel == 175 or MyLevel <= 189 then
                Mon = "Dark Master"
                LevelQuest = 2
                NameQuest = "SkyQuest"
                NameMon = "Dark Master"
                CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
                CFrameMon = CFrame.new(-5259.8447265625, 391.3976745605469, -2229.035400390625)
            elseif MyLevel == 190 or MyLevel <= 209 then
                Mon = "Prisoner"
                LevelQuest = 1
                NameQuest = "PrisonerQuest"
                NameMon = "Prisoner"
                CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)
                CFrameMon = CFrame.new(5098.9736328125, -0.3204058110713959, 474.2373352050781)
            elseif MyLevel == 210 or MyLevel <= 249 then
                Mon = "Dangerous Prisoner"
                LevelQuest = 2
                NameQuest = "PrisonerQuest"
                NameMon = "Dangerous Prisoner"
                CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)
                CFrameMon = CFrame.new(5654.5634765625, 15.633401870727539, 866.2991943359375)
            elseif MyLevel == 250 or MyLevel <= 274 then
                Mon = "Toga Warrior"
                LevelQuest = 1
                NameQuest = "ColosseumQuest"
                NameMon = "Toga Warrior"
                CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
                CFrameMon = CFrame.new(-1820.21484375, 51.68385696411133, -2740.6650390625)
            elseif MyLevel == 275 or MyLevel <= 299 then
                Mon = "Gladiator"
                LevelQuest = 2
                NameQuest = "ColosseumQuest"
                NameMon = "Gladiator"
                CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
                CFrameMon = CFrame.new(-1292.838134765625, 56.380882263183594, -3339.031494140625)
            elseif MyLevel == 300 or MyLevel <= 324 then
                Mon = "Military Soldier"
                LevelQuest = 1
                NameQuest = "MagmaQuest"
                NameMon = "Military Soldier"
                CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
                CFrameMon = CFrame.new(-5411.16455078125, 11.081554412841797, 8454.29296875)
            elseif MyLevel == 325 or MyLevel <= 374 then
                Mon = "Military Spy"
                LevelQuest = 2
                NameQuest = "MagmaQuest"
                NameMon = "Military Spy"
                CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
                CFrameMon = CFrame.new(-5802.8681640625, 86.26241302490234, 8828.859375)
            elseif MyLevel == 375 or MyLevel <= 399 then
                Mon = "Fishman Warrior"
                LevelQuest = 1
                NameQuest = "FishmanQuest"
                NameMon = "Fishman Warrior"
                CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
                CFrameMon = CFrame.new(60878.30078125, 18.482830047607422, 1543.7574462890625)
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
                end
            elseif MyLevel == 400 or MyLevel <= 449 then
                Mon = "Fishman Commando"
                LevelQuest = 2
                NameQuest = "FishmanQuest"
                NameMon = "Fishman Commando"
                CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
                CFrameMon = CFrame.new(61922.6328125, 18.482830047607422, 1493.934326171875)
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
                end
            elseif MyLevel == 450 or MyLevel <= 474 then
                Mon = "God's Guard"
                LevelQuest = 1
                NameQuest = "SkyExp1Quest"
                NameMon = "God's Guard"
                CFrameQuest = CFrame.new(-4721.88867, 843.874695, -1949.96643, 0.996191859, -0, -0.0871884301, 0, 1, -0, 0.0871884301, 0, 0.996191859)
                CFrameMon = CFrame.new(-4710.04296875, 845.2769775390625, -1927.3079833984375)
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
                end
            elseif MyLevel == 475 or MyLevel <= 524 then
                Mon = "Shanda"
                LevelQuest = 2
                NameQuest = "SkyExp1Quest"
                NameMon = "Shanda"
                CFrameQuest = CFrame.new(-7859.09814, 5544.19043, -381.476196, -0.422592998, 0, 0.906319618, 0, 1, 0, -0.906319618, 0, -0.422592998)
                CFrameMon = CFrame.new(-7678.48974609375, 5566.40380859375, -497.2156066894531)
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
                end
            elseif MyLevel == 525 or MyLevel <= 549 then
                Mon = "Royal Squad"
                LevelQuest = 1
                NameQuest = "SkyExp2Quest"
                NameMon = "Royal Squad"
                CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
                CFrameMon = CFrame.new(-7624.25244140625, 5658.13330078125, -1467.354248046875)
            elseif MyLevel == 550 or MyLevel <= 624 then
                Mon = "Royal Soldier"
                LevelQuest = 2
                NameQuest = "SkyExp2Quest"
                NameMon = "Royal Soldier"
                CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
                CFrameMon = CFrame.new(-7836.75341796875, 5645.6640625, -1790.6236572265625)
            elseif MyLevel == 625 or MyLevel <= 649 then
                Mon = "Galley Pirate"
                LevelQuest = 1
                NameQuest = "FountainQuest"
                NameMon = "Galley Pirate"
                CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
                CFrameMon = CFrame.new(5551.02197265625, 78.90135192871094, 3930.412841796875)
            elseif MyLevel >= 650 then
                Mon = "Galley Captain"
                LevelQuest = 2
                NameQuest = "FountainQuest"
                NameMon = "Galley Captain"
                CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
                CFrameMon = CFrame.new(5441.95166015625, 42.50205993652344, 4950.09375)
            end
        elseif World2 then
            if MyLevel == 700 or MyLevel <= 724 then
                Mon = "Raider"
                LevelQuest = 1
                NameQuest = "Area1Quest"
                NameMon = "Raider"
                CFrameQuest = CFrame.new(-429.543518, 71.7699966, 1836.18188, -0.22495985, 0, -0.974368095, 0, 1, 0, 0.974368095, 0, -0.22495985)
                CFrameMon = CFrame.new(-728.3267211914062, 52.779319763183594, 2345.7705078125)
            elseif MyLevel == 725 or MyLevel <= 774 then
                Mon = "Mercenary"
                LevelQuest = 2
                NameQuest = "Area1Quest"
                NameMon = "Mercenary"
                CFrameQuest = CFrame.new(-429.543518, 71.7699966, 1836.18188, -0.22495985, 0, -0.974368095, 0, 1, 0, 0.974368095, 0, -0.22495985)
                CFrameMon = CFrame.new(-1004.3244018554688, 80.15886688232422, 1424.619384765625)
            elseif MyLevel == 775 or MyLevel <= 799 then
                Mon = "Swan Pirate"
                LevelQuest = 1
                NameQuest = "Area2Quest"
                NameMon = "Swan Pirate"
                CFrameQuest = CFrame.new(638.43811, 71.769989, 918.282898, 0.139203906, 0, 0.99026376, 0, 1, 0, -0.99026376, 0, 0.139203906)
                CFrameMon = CFrame.new(1068.664306640625, 137.61428833007812, 1322.1060791015625)
            elseif MyLevel == 800 or MyLevel <= 874 then
                Mon = "Factory Staff"
                NameQuest = "Area2Quest"
                LevelQuest = 2
                NameMon = "Factory Staff"
                CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
                CFrameMon = CFrame.new(73.07867431640625, 81.86344146728516, -27.470672607421875)
            elseif MyLevel == 875 or MyLevel <= 899 then
                Mon = "Marine Lieutenant"
                LevelQuest = 1
                NameQuest = "MarineQuest3"
                NameMon = "Marine Lieutenant"
                CFrameQuest = CFrame.new(-2440.79639, 71.7140732, -3216.06812, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
                CFrameMon = CFrame.new(-2821.372314453125, 75.89727783203125, -3070.089111328125)
            elseif MyLevel == 900 or MyLevel <= 949 then
                Mon = "Marine Captain"
                LevelQuest = 2
                NameQuest = "MarineQuest3"
                NameMon = "Marine Captain"
                CFrameQuest = CFrame.new(-2440.79639, 71.7140732, -3216.06812, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
                CFrameMon = CFrame.new(-1861.2310791015625, 80.17658233642578, -3254.697509765625)
            elseif MyLevel == 950 or MyLevel <= 974 then
                Mon = "Zombie"
                LevelQuest = 1
                NameQuest = "ZombieQuest"
                NameMon = "Zombie"
                CFrameQuest = CFrame.new(-5497.06152, 47.5923004, -795.237061, -0.29242146, 0, -0.95628953, 0, 1, 0, 0.95628953, 0, -0.29242146)
                CFrameMon = CFrame.new(-5657.77685546875, 78.96973419189453, -928.68701171875)
            elseif MyLevel == 975 or MyLevel <= 999 then
                Mon = "Vampire"
                LevelQuest = 2
                NameQuest = "ZombieQuest"
                NameMon = "Vampire"
                CFrameQuest = CFrame.new(-5497.06152, 47.5923004, -795.237061, -0.29242146, 0, -0.95628953, 0, 1, 0, 0.95628953, 0, -0.29242146)
                CFrameMon = CFrame.new(-6037.66796875, 32.18463897705078, -1340.6597900390625)
            elseif MyLevel == 1000 or MyLevel <= 1049 then
                Mon = "Snow Trooper"
                LevelQuest = 1
                NameQuest = "SnowMountainQuest"
                NameMon = "Snow Trooper"
                CFrameQuest = CFrame.new(609.858826, 400.119904, -5372.25928, -0.374604106, 0, 0.92718488, 0, 1, 0, -0.92718488, 0, -0.374604106)
                CFrameMon = CFrame.new(549.1473388671875, 427.3870544433594, -5563.69873046875)
            elseif MyLevel == 1050 or MyLevel <= 1099 then
                Mon = "Winter Warrior"
                LevelQuest = 2
                NameQuest = "SnowMountainQuest"
                NameMon = "Winter Warrior"
                CFrameQuest = CFrame.new(609.858826, 400.119904, -5372.25928, -0.374604106, 0, 0.92718488, 0, 1, 0, -0.92718488, 0, -0.374604106)
                CFrameMon = CFrame.new(1142.7451171875, 475.6398010253906, -5199.41650390625)
            elseif MyLevel == 1100 or MyLevel <= 1124 then
                Mon = "Lab Subordinate"
                LevelQuest = 1
                NameQuest = "IceSideQuest"
                NameMon = "Lab Subordinate"
                CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
                CFrameMon = CFrame.new(-5707.4716796875, 15.951709747314453, -4513.39208984375)
            elseif MyLevel == 1125 or MyLevel <= 1174 then
                Mon = "Horned Warrior"
                LevelQuest = 2
                NameQuest = "IceSideQuest"
                NameMon = "Horned Warrior"
                CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
                CFrameMon = CFrame.new(-6341.36669921875, 15.951770782470703, -5723.162109375)
            elseif MyLevel == 1175 or MyLevel <= 1199 then
                Mon = "Magma Ninja"
                LevelQuest = 1
                NameQuest = "FireSideQuest"
                NameMon = "Magma Ninja"
                CFrameQuest = CFrame.new(-5428.03174, 15.0622921, -5299.43457, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)
                CFrameMon = CFrame.new(-5449.6728515625, 76.65874481201172, -5808.20068359375)
            elseif MyLevel == 1200 or MyLevel <= 1249 then
                Mon = "Lava Pirate"
                LevelQuest = 2
                NameQuest = "FireSideQuest"
                NameMon = "Lava Pirate"
                CFrameQuest = CFrame.new(-5428.03174, 15.0622921, -5299.43457, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)
                CFrameMon = CFrame.new(-5213.33154296875, 49.73788070678711, -4701.451171875)
            elseif MyLevel == 1250 or MyLevel <= 1274 then
                Mon = "Ship Deckhand"
                LevelQuest = 1
                NameQuest = "ShipQuest1"
                NameMon = "Ship Deckhand"
                CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)         
                CFrameMon = CFrame.new(1212.0111083984375, 150.79205322265625, 33059.24609375)    
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
                end
            elseif MyLevel == 1275 or MyLevel <= 1299 then
                Mon = "Ship Engineer"
                LevelQuest = 2
                NameQuest = "ShipQuest1"
                NameMon = "Ship Engineer"
                CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)   
                CFrameMon = CFrame.new(919.4786376953125, 43.54401397705078, 32779.96875)   
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
                end             
            elseif MyLevel == 1300 or MyLevel <= 1324 then
                Mon = "Ship Steward"
                LevelQuest = 1
                NameQuest = "ShipQuest2"
                NameMon = "Ship Steward"
                CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125)         
                CFrameMon = CFrame.new(919.4385375976562, 129.55599975585938, 33436.03515625)      
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
                end
            elseif MyLevel == 1325 or MyLevel <= 1349 then
                Mon = "Ship Officer"
                LevelQuest = 2
                NameQuest = "ShipQuest2"
                NameMon = "Ship Officer"
                CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125)
                CFrameMon = CFrame.new(1036.0179443359375, 181.4390411376953, 33315.7265625)
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
                end
            elseif MyLevel == 1350 or MyLevel <= 1374 then
                Mon = "Arctic Warrior"
                LevelQuest = 1
                NameQuest = "FrostQuest"
                NameMon = "Arctic Warrior"
                CFrameQuest = CFrame.new(5667.6582, 26.7997818, -6486.08984, -0.933587909, 0, -0.358349502, 0, 1, 0, 0.358349502, 0, -0.933587909)
                CFrameMon = CFrame.new(5966.24609375, 62.97002029418945, -6179.3828125)
                if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-6508.5581054688, 5000.034996032715, -132.83953857422))
                end
            elseif MyLevel == 1375 or MyLevel <= 1424 then
                Mon = "Snow Lurker"
                LevelQuest = 2
                NameQuest = "FrostQuest"
                NameMon = "Snow Lurker"
                CFrameQuest = CFrame.new(5667.6582, 26.7997818, -6486.08984, -0.933587909, 0, -0.358349502, 0, 1, 0, 0.358349502, 0, -0.933587909)
                CFrameMon = CFrame.new(5407.07373046875, 69.19437408447266, -6880.88037109375)
            elseif MyLevel == 1425 or MyLevel <= 1449 then
                Mon = "Sea Soldier"
                LevelQuest = 1
                NameQuest = "ForgottenQuest"
                NameMon = "Sea Soldier"
                CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)
                CFrameMon = CFrame.new(-3028.2236328125, 64.67451477050781, -9775.4267578125)
            elseif MyLevel >= 1450 then
                Mon = "Water Fighter"
                LevelQuest = 2
                NameQuest = "ForgottenQuest"
                NameMon = "Water Fighter"
                CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)
                CFrameMon = CFrame.new(-3352.9013671875, 285.01556396484375, -10534.841796875)
            end
        elseif World3 then
            if MyLevel == 1500 or MyLevel <= 1524 then
                Mon = "Pirate Millionaire"
                LevelQuest = 1
                NameQuest = "PiratePortQuest"
                NameMon = "Pirate Millionaire"
                CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
                CFrameMon = CFrame.new(-245.9963836669922, 47.30615234375, 5584.1005859375)
            elseif MyLevel == 1525 or MyLevel <= 1574 then
                Mon = "Pistol Billionaire"
                LevelQuest = 2
                NameQuest = "PiratePortQuest"
                NameMon = "Pistol Billionaire"
                CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
                CFrameMon = CFrame.new(-187.3301544189453, 86.23987579345703, 6013.513671875)
            elseif MyLevel == 1575 or MyLevel <= 1599 then
                Mon = "Dragon Crew Warrior"
                LevelQuest = 1
                NameQuest = "AmazonQuest"
                NameMon = "Dragon Crew Warrior"
                CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563, 0.898790359, -0, -0.438378751, 0, 1, -0, 0.438378751, 0, 0.898790359)
                CFrameMon = CFrame.new(6141.140625, 51.35136413574219, -1340.738525390625)
            elseif MyLevel == 1600 or MyLevel <= 1624 then 
                Mon = "Dragon Crew Archer [Lv. 1600]"
                NameQuest = "AmazonQuest"
                LevelQuest = 2
                NameMon = "Dragon Crew Archer"
                CFrameQuest = CFrame.new(5833.1147460938, 51.60498046875, -1103.0693359375)
                CFrameMon = CFrame.new(6616.41748046875, 441.7670593261719, 446.0469970703125)
            elseif MyLevel == 1625 or MyLevel <= 1649 then
                Mon = "Female Islander"
                NameQuest = "AmazonQuest2"
                LevelQuest = 1
                NameMon = "Female Islander"
                CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
                CFrameMon = CFrame.new(4685.25830078125, 735.8078002929688, 815.3425903320312)
            elseif MyLevel == 1650 or MyLevel <= 1699 then 
                Mon = "Giant Islander [Lv. 1650]"
                NameQuest = "AmazonQuest2"
                LevelQuest = 2
                NameMon = "Giant Islander"
                CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
                CFrameMon = CFrame.new(4729.09423828125, 590.436767578125, -36.97627639770508)
            elseif MyLevel == 1700 or MyLevel <= 1724 then
                Mon = "Marine Commodore"
                LevelQuest = 1
                NameQuest = "MarineTreeIsland"
                NameMon = "Marine Commodore"
                CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498, -0.965929747, 0, 0.258804798, 0, 1, 0, -0.258804798, 0, -0.965929747)
                CFrameMon = CFrame.new(2286.0078125, 73.13391876220703, -7159.80908203125)
            elseif MyLevel == 1725 or MyLevel <= 1774 then
                Mon = "Marine Rear Admiral [Lv. 1725]"
                NameMon = "Marine Rear Admiral"
                NameQuest = "MarineTreeIsland"
                LevelQuest = 2
                CFrameQuest = CFrame.new(2179.98828125, 28.731239318848, -6740.0551757813)
                CFrameMon = CFrame.new(3656.773681640625, 160.52406311035156, -7001.5986328125)
            elseif MyLevel == 1775 or MyLevel <= 1799 then
                Mon = "Fishman Raider"
                LevelQuest = 1
                NameQuest = "DeepForestIsland3"
                NameMon = "Fishman Raider"
                CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)   
                CFrameMon = CFrame.new(-10407.5263671875, 331.76263427734375, -8368.5166015625)
            elseif MyLevel == 1800 or MyLevel <= 1824 then
                Mon = "Fishman Captain"
                LevelQuest = 2
                NameQuest = "DeepForestIsland3"
                NameMon = "Fishman Captain"
                CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)   
                CFrameMon = CFrame.new(-10994.701171875, 352.38140869140625, -9002.1103515625) 
            elseif MyLevel == 1825 or MyLevel <= 1849 then
                Mon = "Forest Pirate"
                LevelQuest = 1
                NameQuest = "DeepForestIsland"
                NameMon = "Forest Pirate"
                CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)
                CFrameMon = CFrame.new(-13274.478515625, 332.3781433105469, -7769.58056640625)
            elseif MyLevel == 1850 or MyLevel <= 1899 then
                Mon = "Mythological Pirate"
                LevelQuest = 2
                NameQuest = "DeepForestIsland"
                NameMon = "Mythological Pirate"
                CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)   
                CFrameMon = CFrame.new(-13680.607421875, 501.08154296875, -6991.189453125)
            elseif MyLevel == 1900 or MyLevel <= 1924 then
                Mon = "Jungle Pirate"
                LevelQuest = 1
                NameQuest = "DeepForestIsland2"
                NameMon = "Jungle Pirate"
                CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)
                CFrameMon = CFrame.new(-12256.16015625, 331.73828125, -10485.8369140625)
            elseif MyLevel == 1925 or MyLevel <= 1974 then
                Mon = "Musketeer Pirate"
                LevelQuest = 2
                NameQuest = "DeepForestIsland2"
                NameMon = "Musketeer Pirate"
                CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)
                CFrameMon = CFrame.new(-13457.904296875, 391.545654296875, -9859.177734375)
            elseif MyLevel == 1975 or MyLevel <= 1999 then
                Mon = "Reborn Skeleton"
                LevelQuest = 1
                NameQuest = "HauntedQuest1"
                NameMon = "Reborn Skeleton"
                CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
                CFrameMon = CFrame.new(-8763.7236328125, 165.72299194335938, 6159.86181640625)
            elseif MyLevel == 2000 or MyLevel <= 2024 then
                Mon = "Living Zombie"
                LevelQuest = 2
                NameQuest = "HauntedQuest1"
                NameMon = "Living Zombie"
                CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
                CFrameMon = CFrame.new(-10144.1318359375, 138.62667846679688, 5838.0888671875)
            elseif MyLevel == 2025 or MyLevel <= 2049 then
                Mon = "Demonic Soul"
                LevelQuest = 1
                NameQuest = "HauntedQuest2"
                NameMon = "Demonic Soul"
                CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0) 
                CFrameMon = CFrame.new(-9505.8720703125, 172.10482788085938, 6158.9931640625)
            elseif MyLevel == 2050 or MyLevel <= 2074 then
                Mon = "Posessed Mummy"
                LevelQuest = 2
                NameQuest = "HauntedQuest2"
                NameMon = "Posessed Mummy"
                CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0)
                CFrameMon = CFrame.new(-9582.0224609375, 6.251527309417725, 6205.478515625)
            elseif MyLevel == 2075 or MyLevel <= 2099 then
                Mon = "Peanut Scout"
                LevelQuest = 1
                NameQuest = "NutsIslandQuest"
                NameMon = "Peanut Scout"
                CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)
                CFrameMon = CFrame.new(-2143.241943359375, 47.72198486328125, -10029.9951171875)
            elseif MyLevel == 2100 or MyLevel <= 2124 then
                Mon = "Peanut President"
                LevelQuest = 2
                NameQuest = "NutsIslandQuest"
                NameMon = "Peanut President"
                CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)
                CFrameMon = CFrame.new(-1859.35400390625, 38.10316848754883, -10422.4296875)
            elseif MyLevel == 2125 or MyLevel <= 2149 then
                Mon = "Ice Cream Chef"
                LevelQuest = 1
                NameQuest = "IceCreamIslandQuest"
                NameMon = "Ice Cream Chef"
                CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)
                CFrameMon = CFrame.new(-872.24658203125, 65.81957244873047, -10919.95703125)
            elseif MyLevel == 2150 or MyLevel <= 2199 then
                Mon = "Ice Cream Commander"
                LevelQuest = 2
                NameQuest = "IceCreamIslandQuest"
                NameMon = "Ice Cream Commander"
                CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)
                CFrameMon = CFrame.new(-558.06103515625, 112.04895782470703, -11290.7744140625)
            elseif MyLevel == 2200 or MyLevel <= 2224 then
                Mon = "Cookie Crafter"
                LevelQuest = 1
                NameQuest = "CakeQuest1"
                NameMon = "Cookie Crafter"
                CFrameQuest = CFrame.new(-2021.32007, 37.7982254, -12028.7295, 0.957576931, -8.80302053e-08, 0.288177818, 6.9301187e-08, 1, 7.51931211e-08, -0.288177818, -5.2032135e-08, 0.957576931)
                CFrameMon = CFrame.new(-2374.13671875, 37.79826354980469, -12125.30859375)
            elseif MyLevel == 2225 or MyLevel <= 2249 then
                Mon = "Cake Guard"
                LevelQuest = 2
                NameQuest = "CakeQuest1"
                NameMon = "Cake Guard"
                CFrameQuest = CFrame.new(-2021.32007, 37.7982254, -12028.7295, 0.957576931, -8.80302053e-08, 0.288177818, 6.9301187e-08, 1, 7.51931211e-08, -0.288177818, -5.2032135e-08, 0.957576931)
                CFrameMon = CFrame.new(-1598.3070068359375, 43.773197174072266, -12244.5810546875)
            elseif MyLevel == 2250 or MyLevel <= 2274 then
                Mon = "Baking Staff"
                LevelQuest = 1
                NameQuest = "CakeQuest2"
                NameMon = "Baking Staff"
                CFrameQuest = CFrame.new(-1927.91602, 37.7981339, -12842.5391, -0.96804446, 4.22142143e-08, 0.250778586, 4.74911062e-08, 1, 1.49904711e-08, -0.250778586, 2.64211941e-08, -0.96804446)
                CFrameMon = CFrame.new(-1887.8099365234375, 77.6185073852539, -12998.3505859375)
            elseif MyLevel == 2275 or MyLevel <= 2299 then
                Mon = "Head Baker"
                LevelQuest = 2
                NameQuest = "CakeQuest2"
                NameMon = "Head Baker"
                CFrameQuest = CFrame.new(-1927.91602, 37.7981339, -12842.5391, -0.96804446, 4.22142143e-08, 0.250778586, 4.74911062e-08, 1, 1.49904711e-08, -0.250778586, 2.64211941e-08, -0.96804446)
                CFrameMon = CFrame.new(-2216.188232421875, 82.884521484375, -12869.2939453125)
            elseif MyLevel == 2300 or MyLevel <= 2324 then
                Mon = "Cocoa Warrior"
                LevelQuest = 1
                NameQuest = "ChocQuest1"
                NameMon = "Cocoa Warrior"
                CFrameQuest = CFrame.new(233.22836303710938, 29.876001358032227, -12201.2333984375)
                CFrameMon = CFrame.new(-21.55328369140625, 80.57499694824219, -12352.3876953125)
            elseif MyLevel == 2325 or MyLevel <= 2349 then
                Mon = "Chocolate Bar Battler"
                LevelQuest = 2
                NameQuest = "ChocQuest1"
                NameMon = "Chocolate Bar Battler"
                CFrameQuest = CFrame.new(233.22836303710938, 29.876001358032227, -12201.2333984375)
                CFrameMon = CFrame.new(582.590576171875, 77.18809509277344, -12463.162109375)
            elseif MyLevel == 2350 or MyLevel <= 2374 then
                Mon = "Sweet Thief"
                LevelQuest = 1
                NameQuest = "ChocQuest2"
                NameMon = "Sweet Thief"
                CFrameQuest = CFrame.new(150.5066375732422, 30.693693161010742, -12774.5029296875)
                CFrameMon = CFrame.new(165.1884765625, 76.05885314941406, -12600.8369140625)
            elseif MyLevel == 2375 or MyLevel <= 2399 then
                Mon = "Candy Rebel"
                LevelQuest = 2
                NameQuest = "ChocQuest2"
                NameMon = "Candy Rebel"
                CFrameQuest = CFrame.new(150.5066375732422, 30.693693161010742, -12774.5029296875)
                CFrameMon = CFrame.new(134.86563110351562, 77.2476806640625, -12876.5478515625)
            elseif MyLevel == 2400 or MyLevel <= 2424 then
                Mon = "Candy Pirate"
                LevelQuest = 1
                NameQuest = "CandyQuest1"
                NameMon = "Candy Pirate"
                CFrameQuest = CFrame.new(-1150.0400390625, 20.378934860229492, -14446.3349609375)
                CFrameMon = CFrame.new(-1310.5003662109375, 26.016523361206055, -14562.404296875)
            elseif MyLevel == 2425 or MyLevel <= 2449 then
                Mon = "Snow Demon"
                LevelQuest = 2
                NameQuest = "CandyQuest1"
                NameMon = "Snow Demon"
                CFrameQuest = CFrame.new(-1150.0400390625, 20.378934860229492, -14446.3349609375)
                CFrameMon = CFrame.new(-880.2006225585938, 71.24776458740234, -14538.609375)
            elseif MyLevel == 2450 or MyLevel <= 2474 then
                Mon = "Isle Outlaw"
                LevelQuest = 1
                NameQuest = "TikiQuest1"
                NameMon = "Isle Outlaw"
                CFrameQuest = CFrame.new(-16547.748046875, 61.13533401489258, -173.41360473632812)
                CFrameMon = CFrame.new(-16442.814453125, 116.13899993896484, -264.4637756347656)
            elseif MyLevel == 2475 or MyLevel <= 2499 then
                Mon = "Island Boy"
                LevelQuest = 2
                NameQuest = "TikiQuest1"
                NameMon = "Island Boy"
                CFrameQuest = CFrame.new(-16547.748046875, 61.13533401489258, -173.41360473632812)
                CFrameMon = CFrame.new(-16901.26171875, 84.06756591796875, -192.88906860351562)
            elseif MyLevel == 2500 or MyLevel <= 2524 then
                Mon = "Sun-kissed Warrior"
                LevelQuest = 1
                NameQuest = "TikiQuest2"
                NameMon = "Sun-kissed Warrior"
                CFrameQuest = CFrame.new(-16539.078125, 55.68632888793945, 1051.5738525390625)
                CFrameMon = CFrame.new(-16349.8779296875, 92.0808334350586, 1123.4169921875)
            elseif MyLevel == 2525 or MyLevel <= 2550 then
                Mon = "Isle Champion"
                LevelQuest = 2
                NameQuest = "TikiQuest2"
                NameMon = "Isle Champion"
                CFrameQuest = CFrame.new(-16539.078125, 55.68632888793945, 1051.5738525390625)
                CFrameMon = CFrame.new(-16347.4150390625, 92.09503936767578, 1122.335205078125)
            end
        end
    end
    
    function BTP(Position)
	game.Players.LocalPlayer.Character.Head:Destroy()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Position
	wait(1)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Position
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
    end
    
    local function toTarget(...)
	local RealtargetPos = {...}
	local targetPos = RealtargetPos[1]
	local RealTarget
	if type(targetPos) == "vector" then
		RealTarget = CFrame.new(targetPos)
	elseif type(targetPos) == "userdata" then
		RealTarget = targetPos
	elseif type(targetPos) == "number" then
		RealTarget = CFrame.new(unpack(RealtargetPos))
	end

	if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health == 0 then if tween then tween:Cancel() end repeat wait() until game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health > 0; wait(0.2) end

	local tweenfunc = {}
	local Distance = (RealTarget.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).Magnitude
	if Distance < 1000 then
		Speed = 315
	elseif Distance >= 1000 then
		Speed = 300
	end

	if _G.Settings.Configs["Bypass TP"] then
		if Distance > 3000 and not AutoFarmMaterial and not _G.Settings.FightingStyle["Auto God Human"] and not _G.Settings.Raids["Auto Raids"] and not (game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") or game.Players.LocalPlayer.Character:FindFirstChild("Special Microchip") or game.Players.LocalPlayer.Backpack:FindFirstChild("God's Chalice") or game.Players.LocalPlayer.Character:FindFirstChild("God's Chalice") or game.Players.LocalPlayer.Backpack:FindFirstChild("Hallow Essence") or game.Players.LocalPlayer.Character:FindFirstChild("Hallow Essence") or game.Players.LocalPlayer.Character:FindFirstChild("Sweet Chalice") or game.Players.LocalPlayer.Backpack:FindFirstChild("Sweet Chalice")) and not (Name == "Fishman Commando [Lv. 400]" or Name == "Fishman Warrior [Lv. 375]") then
			pcall(function()
				tween:Cancel()
				fkwarp = false

				if game:GetService("Players")["LocalPlayer"].Data:FindFirstChild("SpawnPoint").Value == tostring(GetIsLand(RealTarget)) then 
					wait(.1)
					Com("F_","TeleportToSpawn")
				elseif game:GetService("Players")["LocalPlayer"].Data:FindFirstChild("LastSpawnPoint").Value == tostring(GetIsLand(RealTarget)) then
					game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(15)
					wait(0.1)
					repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
				else
					if game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 then
						if fkwarp == false then
							game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = RealTarget
						end
						fkwarp = true
					end
					wait(.08)
					game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(15)
					repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
					wait(.1)
					Com("F_","SetSpawnPoint")
				end
				wait(0.2)

				return
			end)
		end
	end

	local tween_s = game:service"TweenService"
	local info = TweenInfo.new((RealTarget.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).Magnitude/Speed, Enum.EasingStyle.Linear)
	local tweenw, err = pcall(function()
		tween = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = RealTarget})
		tween:Play()
	end)

	function tweenfunc:Stop()
		tween:Cancel()
	end 

	function tweenfunc:Wait()
		tween.Completed:Wait()
	end 

	return tweenfunc
end

function toTargetP(CFgo)
	if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health <= 0 or not game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") then tween:Cancel() repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") and game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 wait(7) return end
	if (game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - CFgo.Position).Magnitude <= 150 then
		pcall(function()
			tween:Cancel()

			game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.CFrame = CFgo

			return
		end)
	end
	local tween_s = game:service"TweenService"
	local info = TweenInfo.new((game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - CFgo.Position).Magnitude/325, Enum.EasingStyle.Linear)
	tween = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = CFgo})
	tween:Play()

	local tweenfunc = {}

	function tweenfunc:Stop()
		tween:Cancel()
	end

	return tweenfunc
end

function UnEquipWeapon(Weapon)
    if game.Players.LocalPlayer.Character:FindFirstChild(Weapon) then
        _G.NotAutoEquip = true
        wait(.5)
        game.Players.LocalPlayer.Character:FindFirstChild(Weapon).Parent = game.Players.LocalPlayer.Backpack
        wait(.1)
        _G.NotAutoEquip = false
    end
end

function EquipWeapon(ToolSe)
        if not _G.NotAutoEquip then
            if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
                Tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
                wait(.1)
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tool)
            end
        end
    end

  getgenv().ToTarget=function(Pos)
    Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        if game.Players.LocalPlayer.Character.Humanoid.Sit == true then game.Players.LocalPlayer.Character.Humanoid.Sit = false end
        pcall(function() tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart,TweenInfo.new(Distance/350, Enum.EasingStyle.Linear),{CFrame = Pos}) end)
        tween:Play()
        if Distance <= 250 then
            tween:Cancel()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
        end
        if _G.StopTween == true then
            tween:Cancel()
            _G.Clip = false
        end
     end
	
 spawn(function()
    game:GetService("RunService").Heartbeat:Connect(function()
        if _G.Auto_Farm_Level or _G.AutoSaber or _G.AutoSaberHop or _G.AutoPole or _G.AutoPoleHop or _G.Next_Island or _G.AutoFarmBoss or _G.AutoFarmBossAll or _G.Teleport_to_Sea_Beast or _G.Teleport or _G.AutoSharkman or _G.AutoElectricClaw then
            if not game:GetService("Workspace"):FindFirstChild("Part") then
                local Part = Instance.new("Part")
                Part.Name = "Part"
                Part.Parent = game.Workspace
                Part.Anchored = true
				Part.Color = Color3.fromRGB(255, 255, 0)
                Part.Transparency = 1
                Part.Size = Vector3.new(40,40,40)
            elseif game:GetService("Workspace"):FindFirstChild("Part") then
                game.Workspace["Part"].CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.X,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Y - 3.92,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Z)
            end
        else
            if game:GetService("Workspace"):FindFirstChild("Part") then
                game:GetService("Workspace"):FindFirstChild("Part"):Destroy()
            end
        end
    end)
end)
spawn(function()
    game:GetService("RunService").Stepped:Connect(function()
        if _G.Auto_Farm_Level or _G.AutoSaber or _G.AutoSaberHop or _G.AutoPole or _G.AutoPoleHop or _G.Next_Island or _G.AutoFarmBoss or _G.AutoFarmBossAll or _G.Teleport_to_Sea_Beast or _G.Teleport or _G.AutoSharkman or _G.AutoElectricClaw then
            for _, v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
                if v:IsA("BasePart") then
                    v.CanCollide = false    
                end
            end
        end
    end)
end)
function changestate()
    game.Workspace["Part"].CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.X,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Y - 3.92,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Z)
end
spawn(function()
	pcall(function()
		while wait() do
			if _G.Auto_Farm_Level or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.StartKaitan or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.AutoFarmBone or _G.Autoheart or _G.Autodoughking or _G.AutoFarmMaterial or _G.AutoNevaSoulGuitar or _G.Auto_Dragon_Trident or _G.Autotushita or _G.d or _G.Autowaden or _G.Autogay or _G.Autopole or _G.Autosaw or _G.AutoObservationHakiV2 or _G.AutoFarmNearest or AutoFarmChest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Tweenfruit or _G.AutoFactory or _G.TeleportNPC or AutoGodhuman == true then
				if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
					local Noclip = Instance.new("BodyVelocity")
					Noclip.Name = "BodyClip"
					Noclip.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
					Noclip.MaxForce = Vector3.new(100000,100000,100000)
					Noclip.Velocity = Vector3.new(0,0,0)
				end
			end
		end
	end)
end)

spawn(function()
	pcall(function()
		game:GetService("RunService").Stepped:Connect(function()
			if _G.Auto_Farm_Level or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.StartKaitan or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.AutoFarmBone or _G.Autoheart or _G.Autodoughking or _G.AutoFarmMaterial or _G.AutoNevaSoulGuitar or _G.Auto_Dragon_Trident or _G.Autotushita or _G.Autowaden or _G.Autogay or _G.Autopole or _G.Autosaw or _G.AutoObservationHakiV2 or _G.AutoFarmNearest or AutoFarmChest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Tweenfruit or _G.AutoFactory or _G.TeleportNPC or AutoGodhuman == true then
				for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do
					if v:IsA("BasePart") then
						v.CanCollide = false    
					end
				end
			end
		end)
	end)
end)

spawn(function()
	while wait() do
		if _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.AutoFarmBone or _G.Autoheart or _G.Autodoughking or _G.d or _G.Autowaden or _G.Autogay or _G.AutoObservationHakiV2 or _G.AutoFarmMaterial or _G.AutoFarmNearest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.AutoFactory or AutoGodhuman == true then
			pcall(function()
				game:GetService("ReplicatedStorage").Remotes.CommE:FireServer("Ken",true)
			end)
		end    
	end
end)
spawn(function()
    while task.wait() do
        pcall(function()
            if _G.Auto_Farm_Level or _G.AutoSaber or _G.AutoSaberHop or _G.AutoPole or _G.AutoPoleHop or _G.Next_Island or _G.AutoFarmBoss or _G.AutoFarmBossAll or _G.Teleport_to_Sea_Beast or _G.Teleport or _G.AutoSharkman or _G.AutoElectricClaw then
                if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    local Noclip = Instance.new("BodyVelocity")
                    Noclip.Name = "BodyClip"
                    Noclip.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                    Noclip.MaxForce = Vector3.new(100000,100000,100000)
                    Noclip.Velocity = Vector3.new(0,0,0)
                end
            else
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()
            end
        end)
    end
end)

function CheckMaterial(matname)
	for i,v in pairs(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventory")) do
		if type(v) == "table" then
			if v.Type == "Material" then
				if v.Name == matname then
					return v.Count
				end
			end
		end
	end
	return 0
end

function TPPlayer(Pos)
    repeat wait()
        Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        if game.Players.LocalPlayer.Character.Humanoid.Sit == true then game.Players.LocalPlayer.Character.Humanoid.Sit = false end
        pcall(function() tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart,TweenInfo.new(Distance/200, Enum.EasingStyle.Linear),{CFrame = Pos}) end)
        tween:Play()
        if Distance <= 350 then
            tween:Cancel()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
        end
        if Distance >= 3000 then
	    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
	    wait(1)
	    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
	    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
        end
        if _G.StopTween == true then
            tween:Cancel()
            _G.Clip = false
        end
    until Distance <= 3000
end
function StopTween(target)
    if not target then
        _G.StopTween = true
        wait()
        topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
        wait()
        if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()
        end
        _G.StopTween = false
        _G.Clip = false
    end
end
spawn(function()
    pcall(function()
        while wait() do
            for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do  
                if v:IsA("Tool") then
                    if v:FindFirstChild("RemoteFunctionShoot") then 
                        SelectWeaponGun = v.Name
                    end
                end
            end
        end
    end)
end)
function TelePPlayer(P)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
end
    
    function TP(Pos)
    Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 25 then
        Speed = 10000
    elseif Distance < 50 then
        Speed = 2000
    elseif Distance < 150 then
        Speed = 800
    elseif Distance < 250 then
        Speed = 600
    elseif Distance < 500 then
        Speed = 400
    elseif Distance < 750 then
        Speed = 250
    elseif Distance >= 1000 then
        Speed = 200
    end
    game:GetService("TweenService"):Create(
        game.Players.LocalPlayer.Character.HumanoidRootPart,
        TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
        {CFrame = Pos}
    ):Play()
end

    function TP1(Pos)
        Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        if Distance < 25 then
            Speed = 5000
        elseif Distance < 50 then
            Speed = 2000
        elseif Distance < 150 then
            Speed = 800
        elseif Distance < 250 then
            Speed = 600
        elseif Distance < 500 then
            Speed = 300
        elseif Distance < 750 then
            Speed = 250
        elseif Distance >= 1000 then
            Speed = 200
        end
        game:GetService("TweenService"):Create(
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
            {CFrame = Pos}
        ):Play()
end

function topos(Pos)
        Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        if Distance < 25 then
            Speed = 5000
        elseif Distance < 50 then
            Speed = 2000
        elseif Distance < 150 then
            Speed = 800
        elseif Distance < 250 then
            Speed = 600
        elseif Distance < 500 then
            Speed = 300
        elseif Distance < 750 then
            Speed = 250
        elseif Distance >= 1000 then
            Speed = 200
        end
        game:GetService("TweenService"):Create(
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
            {CFrame = Pos}
        ):Play()
end

function TPB(CFgo)
	local tween_s = game:service"TweenService"
	local info = TweenInfo.new((game:GetService("Workspace").Boats.MarineBrigade.VehicleSeat.CFrame.Position - CFgo.Position).Magnitude/300, Enum.EasingStyle.Linear)
	tween = tween_s:Create(game:GetService("Workspace").Boats.MarineBrigade.VehicleSeat, info, {CFrame = CFgo})
	tween:Play()

	local tweenfunc = {}

	function tweenfunc:Stop()
		tween:Cancel()
	end

	return tweenfunc
end

function TPP(CFgo)
	if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health <= 0 or not game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") then tween:Cancel() repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") and game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 wait(7) return end
	local tween_s = game:service"TweenService"
	local info = TweenInfo.new((game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - CFgo.Position).Magnitude/325, Enum.EasingStyle.Linear)
	tween = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = CFgo})
	tween:Play()

	local tweenfunc = {}

	function tweenfunc:Stop()
		tween:Cancel()
	end

	return tweenfunc
end

getgenv().ToTargets = function(p)
    task.spawn(function()
        pcall(function()
            if game:GetService("Players").LocalPlayer:DistanceFromCharacter(p.Position) <= 250 then 
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = p
            elseif not game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
                local K = Instance.new("Part",game.Players.LocalPlayer.Character)
                K.Size = Vector3.new(1,0.5,1)
                K.Name = "Root"
                K.Anchored = true
                K.Transparency = 1
                K.CanCollide = false
                K.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,20,0)
            end
            local U = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude
            local z = game:service("TweenService")
            local B = TweenInfo.new((p.Position-game.Players.LocalPlayer.Character.Root.Position).Magnitude/300,Enum.EasingStyle.Linear)
            local S,g = pcall(function()
            local q = z:Create(game.Players.LocalPlayer.Character.Root,B,{CFrame = p})
            q:Play()
        end)
        if not S then 
            return g
        end
        game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
            if S and game.Players.LocalPlayer.Character:FindFirstChild("Root") then 
                pcall(function()
                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 20 then 
                        spawn(function()
                            pcall(function()
                                if (game.Players.LocalPlayer.Character.Root.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 150 then 
                                    game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                                else 
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=game.Players.LocalPlayer.Character.Root.CFrame
                                end
                            end)
                        end)
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 10 and(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 20 then 
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 10 then 
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p
                    end
                end)
            end
	    end)
    end)
    end
    function Hop()
        local PlaceID = game.PlaceId
        local AllIDs = {}
        local foundAnything = ""
        local actualHour = os.date("!*t").hour
        local Deleted = false
        function TPReturner()
            local Site;
            if foundAnything == "" then
                Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100'))
            else
                Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100&cursor=' .. foundAnything))
            end
            local ID = ""
            if Site.nextPageCursor and Site.nextPageCursor ~= "null" and Site.nextPageCursor ~= nil then
                foundAnything = Site.nextPageCursor
            end
            local num = 0;
            for i,v in pairs(Site.data) do
                local Possible = true
                ID = tostring(v.id)
                if tonumber(v.maxPlayers) > tonumber(v.playing) then
                    for _,Existing in pairs(AllIDs) do
                        if num ~= 0 then
                            if ID == tostring(Existing) then
                                Possible = false
                            end
                        else
                            if tonumber(actualHour) ~= tonumber(Existing) then
                                local delFile = pcall(function()
                                    AllIDs = {}
                                    table.insert(AllIDs, actualHour)
                                end)
                            end
                        end
                        num = num + 1
                    end
                    if Possible == true then
                        table.insert(AllIDs, ID)
                        wait()
                        pcall(function()
                            wait()
                            game:GetService("TeleportService"):TeleportToPlaceInstance(PlaceID, ID, game.Players.LocalPlayer)
                        end)
                        wait(4)
                    end
                end
            end
        end
        function Teleport() 
            while wait() do
                pcall(function()
                    TPReturner()
                    if foundAnything ~= "" then
                        TPReturner()
                    end
                end)
            end
        end
        Teleport()
    end       
    
    function UpdateIslandESP() 
        for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do
            pcall(function()
                if IslandESP then 
                    if v.Name ~= "Sea" then
                        if not v:FindFirstChild('NameEsp') then
                            local bill = Instance.new('BillboardGui',v)
                            bill.Name = 'NameEsp'
                            bill.ExtentsOffset = Vector3.new(0, 1, 0)
                            bill.Size = UDim2.new(1,200,1,30)
                            bill.Adornee = v
                            bill.AlwaysOnTop = true
                            local name = Instance.new('TextLabel',bill)
                            name.Font = "GothamBold"
                            name.FontSize = "Size14"
                            name.TextWrapped = true
                            name.Size = UDim2.new(1,0,1,0)
                            name.TextYAlignment = 'Top'
                            name.BackgroundTransparency = 1
                            name.TextStrokeTransparency = 0.5
                            name.TextColor3 = Color3.fromRGB(7, 236, 240)
                        else
                            v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
                        end
                    end
                else
                    if v:FindFirstChild('NameEsp') then
                        v:FindFirstChild('NameEsp'):Destroy()
                    end
                end
            end)
        end
    end
    
    function isnil(thing)
	return (thing == nil)
end
local function round(n)
	return math.floor(tonumber(n) + 0.5)
end
Number = math.random(1, 1000000)
function UpdatePlayerChams()
	for i,v in pairs(game:GetService'Players':GetChildren()) do
		pcall(function()
			if not isnil(v.Character) then
				if ESPPlayer then
					if not isnil(v.Character.Head) and not v.Character.Head:FindFirstChild('NameEsp'..Number) then
						local bill = Instance.new('BillboardGui',v.Character.Head)
						bill.Name = 'NameEsp'..Number
						bill.ExtentsOffset = Vector3.new(0, 1, 0)
						bill.Size = UDim2.new(1,200,1,30)
						bill.Adornee = v.Character.Head
						bill.AlwaysOnTop = true
						local name = Instance.new('TextLabel',bill)
						name.Font = Enum.Font.GothamSemibold
						name.FontSize = "Size14"
						name.TextWrapped = true
						name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance')
						name.Size = UDim2.new(1,0,1,0)
						name.TextYAlignment = 'Top'
						name.BackgroundTransparency = 1
						name.TextStrokeTransparency = 0.5
						if v.Team == game.Players.LocalPlayer.Team then
							name.TextColor3 = Color3.new(0,255,0)
						else
							name.TextColor3 = Color3.new(255,0,0)
						end
					else
						v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..' | '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance\nHealth : ' .. round(v.Character.Humanoid.Health*100/v.Character.Humanoid.MaxHealth) .. '%')
					end
				else
					if v.Character.Head:FindFirstChild('NameEsp'..Number) then
						v.Character.Head:FindFirstChild('NameEsp'..Number):Destroy()
					end
				end
			end
		end)
	end
end
function UpdateChestChams() 
	for i,v in pairs(game.Workspace:GetChildren()) do
		pcall(function()
			if string.find(v.Name,"Chest") then
				if ChestESP then
					if string.find(v.Name,"Chest") then
						if not v:FindFirstChild('NameEsp'..Number) then
							local bill = Instance.new('BillboardGui',v)
							bill.Name = 'NameEsp'..Number
							bill.ExtentsOffset = Vector3.new(0, 1, 0)
							bill.Size = UDim2.new(1,200,1,30)
							bill.Adornee = v
							bill.AlwaysOnTop = true
							local name = Instance.new('TextLabel',bill)
							name.Font = Enum.Font.GothamSemibold
							name.FontSize = "Size14"
							name.TextWrapped = true
							name.Size = UDim2.new(1,0,1,0)
							name.TextYAlignment = 'Top'
							name.BackgroundTransparency = 1
							name.TextStrokeTransparency = 0.5
							if v.Name == "Chest1" then
								name.TextColor3 = Color3.fromRGB(109, 109, 109)
								name.Text = ("Chest 1" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							end
							if v.Name == "Chest2" then
								name.TextColor3 = Color3.fromRGB(173, 158, 21)
								name.Text = ("Chest 2" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							end
							if v.Name == "Chest3" then
								name.TextColor3 = Color3.fromRGB(85, 255, 255)
								name.Text = ("Chest 3" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							end
						else
							v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
						end
					end
				else
					if v:FindFirstChild('NameEsp'..Number) then
						v:FindFirstChild('NameEsp'..Number):Destroy()
					end
				end
			end
		end)
	end
end
function UpdateDevilChams() 
	for i,v in pairs(game.Workspace:GetChildren()) do
		pcall(function()
			if DevilFruitESP then
				if string.find(v.Name, "Fruit") then   
					if not v.Handle:FindFirstChild('NameEsp'..Number) then
						local bill = Instance.new('BillboardGui',v.Handle)
						bill.Name = 'NameEsp'..Number
						bill.ExtentsOffset = Vector3.new(0, 1, 0)
						bill.Size = UDim2.new(1,200,1,30)
						bill.Adornee = v.Handle
						bill.AlwaysOnTop = true
						local name = Instance.new('TextLabel',bill)
						name.Font = Enum.Font.GothamSemibold
						name.FontSize = "Size14"
						name.TextWrapped = true
						name.Size = UDim2.new(1,0,1,0)
						name.TextYAlignment = 'Top'
						name.BackgroundTransparency = 1
						name.TextStrokeTransparency = 0.5
						name.TextColor3 = Color3.fromRGB(255, 255, 255)
						name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
					else
						v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
					end
				end
			else
				if v.Handle:FindFirstChild('NameEsp'..Number) then
					v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
				end
			end
		end)
	end
end
function UpdateFlowerChams() 
	for i,v in pairs(game.Workspace:GetChildren()) do
		pcall(function()
			if v.Name == "Flower2" or v.Name == "Flower1" then
				if FlowerESP then 
					if not v:FindFirstChild('NameEsp'..Number) then
						local bill = Instance.new('BillboardGui',v)
						bill.Name = 'NameEsp'..Number
						bill.ExtentsOffset = Vector3.new(0, 1, 0)
						bill.Size = UDim2.new(1,200,1,30)
						bill.Adornee = v
						bill.AlwaysOnTop = true
						local name = Instance.new('TextLabel',bill)
						name.Font = Enum.Font.GothamSemibold
						name.FontSize = "Size14"
						name.TextWrapped = true
						name.Size = UDim2.new(1,0,1,0)
						name.TextYAlignment = 'Top'
						name.BackgroundTransparency = 1
						name.TextStrokeTransparency = 0.5
						name.TextColor3 = Color3.fromRGB(255, 0, 0)
						if v.Name == "Flower1" then 
							name.Text = ("Blue Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							name.TextColor3 = Color3.fromRGB(0, 0, 255)
						end
						if v.Name == "Flower2" then
							name.Text = ("Red Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							name.TextColor3 = Color3.fromRGB(255, 0, 0)
						end
					else
						v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
					end
				else
					if v:FindFirstChild('NameEsp'..Number) then
					v:FindFirstChild('NameEsp'..Number):Destroy()
					end
				end
			end   
		end)
	end
end
function UpdateRealFruitChams() 
	for i,v in pairs(game.Workspace.AppleSpawner:GetChildren()) do
		if v:IsA("Tool") then
			if RealFruitESP then 
				if not v.Handle:FindFirstChild('NameEsp'..Number) then
					local bill = Instance.new('BillboardGui',v.Handle)
					bill.Name = 'NameEsp'..Number
					bill.ExtentsOffset = Vector3.new(0, 1, 0)
					bill.Size = UDim2.new(1,200,1,30)
					bill.Adornee = v.Handle
					bill.AlwaysOnTop = true
					local name = Instance.new('TextLabel',bill)
					name.Font = Enum.Font.GothamSemibold
					name.FontSize = "Size14"
					name.TextWrapped = true
					name.Size = UDim2.new(1,0,1,0)
					name.TextYAlignment = 'Top'
					name.BackgroundTransparency = 1
					name.TextStrokeTransparency = 0.5
					name.TextColor3 = Color3.fromRGB(255, 0, 0)
					name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				else
					v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				end
			else
				if v.Handle:FindFirstChild('NameEsp'..Number) then
					v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
				end
			end 
		end
	end
	for i,v in pairs(game.Workspace.PineappleSpawner:GetChildren()) do
		if v:IsA("Tool") then
			if RealFruitESP then 
				if not v.Handle:FindFirstChild('NameEsp'..Number) then
					local bill = Instance.new('BillboardGui',v.Handle)
					bill.Name = 'NameEsp'..Number
					bill.ExtentsOffset = Vector3.new(0, 1, 0)
					bill.Size = UDim2.new(1,200,1,30)
					bill.Adornee = v.Handle
					bill.AlwaysOnTop = true
					local name = Instance.new('TextLabel',bill)
					name.Font = Enum.Font.GothamSemibold
					name.FontSize = "Size14"
					name.TextWrapped = true
					name.Size = UDim2.new(1,0,1,0)
					name.TextYAlignment = 'Top'
					name.BackgroundTransparency = 1
					name.TextStrokeTransparency = 0.5
					name.TextColor3 = Color3.fromRGB(255, 174, 0)
					name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				else
					v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				end
			else
				if v.Handle:FindFirstChild('NameEsp'..Number) then
					v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
				end
			end 
		end
	end
	for i,v in pairs(game.Workspace.BananaSpawner:GetChildren()) do
		if v:IsA("Tool") then
			if RealFruitESP then 
				if not v.Handle:FindFirstChild('NameEsp'..Number) then
					local bill = Instance.new('BillboardGui',v.Handle)
					bill.Name = 'NameEsp'..Number
					bill.ExtentsOffset = Vector3.new(0, 1, 0)
					bill.Size = UDim2.new(1,200,1,30)
					bill.Adornee = v.Handle
					bill.AlwaysOnTop = true
					local name = Instance.new('TextLabel',bill)
					name.Font = Enum.Font.GothamSemibold
					name.FontSize = "Size14"
					name.TextWrapped = true
					name.Size = UDim2.new(1,0,1,0)
					name.TextYAlignment = 'Top'
					name.BackgroundTransparency = 1
					name.TextStrokeTransparency = 0.5
					name.TextColor3 = Color3.fromRGB(251, 255, 0)
					name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				else
					v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				end
			else
				if v.Handle:FindFirstChild('NameEsp'..Number) then
					v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
				end
			end 
		end
	end
end

function UpdateIslandESP() 
        for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do
            pcall(function()
                if IslandESP then 
                    if v.Name ~= "Sea" then
                        if not v:FindFirstChild('NameEsp') then
                            local bill = Instance.new('BillboardGui',v)
                            bill.Name = 'NameEsp'
                            bill.ExtentsOffset = Vector3.new(0, 1, 0)
                            bill.Size = UDim2.new(1,200,1,30)
                            bill.Adornee = v
                            bill.AlwaysOnTop = true
                            local name = Instance.new('TextLabel',bill)
                            name.Font = "GothamBold"
                            name.FontSize = "Size14"
                            name.TextWrapped = true
                            name.Size = UDim2.new(1,0,1,0)
                            name.TextYAlignment = 'Top'
                            name.BackgroundTransparency = 1
                            name.TextStrokeTransparency = 0.5
                            name.TextColor3 = Color3.fromRGB(7, 236, 240)
                        else
                            v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
                        end
                    end
                else
                    if v:FindFirstChild('NameEsp') then
                        v:FindFirstChild('NameEsp'):Destroy()
                    end
                end
            end)
        end
    end
    
    
    function isnil(thing)
	return (thing == nil)
end
local function round(n)
	return math.floor(tonumber(n) + 0.5)
end
Number = math.random(1, 1000000)
function UpdatePlayerChams()
	for i,v in pairs(game:GetService'Players':GetChildren()) do
		pcall(function()
			if not isnil(v.Character) then
				if ESPPlayer then
					if not isnil(v.Character.Head) and not v.Character.Head:FindFirstChild('NameEsp'..Number) then
						local bill = Instance.new('BillboardGui',v.Character.Head)
						bill.Name = 'NameEsp'..Number
						bill.ExtentsOffset = Vector3.new(0, 1, 0)
						bill.Size = UDim2.new(1,200,1,30)
						bill.Adornee = v.Character.Head
						bill.AlwaysOnTop = true
						local name = Instance.new('TextLabel',bill)
						name.Font = Enum.Font.GothamSemibold
						name.FontSize = "Size14"
						name.TextWrapped = true
						name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance')
						name.Size = UDim2.new(1,0,1,0)
						name.TextYAlignment = 'Top'
						name.BackgroundTransparency = 1
						name.TextStrokeTransparency = 0.5
						if v.Team == game.Players.LocalPlayer.Team then
							name.TextColor3 = Color3.new(0,255,0)
						else
							name.TextColor3 = Color3.new(255,0,0)
						end
					else
						v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..' | '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance\nHealth : ' .. round(v.Character.Humanoid.Health*100/v.Character.Humanoid.MaxHealth) .. '%')
					end
				else
					if v.Character.Head:FindFirstChild('NameEsp'..Number) then
						v.Character.Head:FindFirstChild('NameEsp'..Number):Destroy()
					end
				end
			end
		end)
	end
end
function UpdateChestChams() 
	for i,v in pairs(game.Workspace:GetChildren()) do
		pcall(function()
			if string.find(v.Name,"Chest") then
				if ChestESP then
					if string.find(v.Name,"Chest") then
						if not v:FindFirstChild('NameEsp'..Number) then
							local bill = Instance.new('BillboardGui',v)
							bill.Name = 'NameEsp'..Number
							bill.ExtentsOffset = Vector3.new(0, 1, 0)
							bill.Size = UDim2.new(1,200,1,30)
							bill.Adornee = v
							bill.AlwaysOnTop = true
							local name = Instance.new('TextLabel',bill)
							name.Font = Enum.Font.GothamSemibold
							name.FontSize = "Size14"
							name.TextWrapped = true
							name.Size = UDim2.new(1,0,1,0)
							name.TextYAlignment = 'Top'
							name.BackgroundTransparency = 1
							name.TextStrokeTransparency = 0.5
							if v.Name == "Chest1" then
								name.TextColor3 = Color3.fromRGB(109, 109, 109)
								name.Text = ("Chest 1" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							end
							if v.Name == "Chest2" then
								name.TextColor3 = Color3.fromRGB(173, 158, 21)
								name.Text = ("Chest 2" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							end
							if v.Name == "Chest3" then
								name.TextColor3 = Color3.fromRGB(85, 255, 255)
								name.Text = ("Chest 3" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							end
						else
							v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
						end
					end
				else
					if v:FindFirstChild('NameEsp'..Number) then
						v:FindFirstChild('NameEsp'..Number):Destroy()
					end
				end
			end
		end)
	end
end
function UpdateDevilChams() 
	for i,v in pairs(game.Workspace:GetChildren()) do
		pcall(function()
			if DevilFruitESP then
				if string.find(v.Name, "Fruit") then   
					if not v.Handle:FindFirstChild('NameEsp'..Number) then
						local bill = Instance.new('BillboardGui',v.Handle)
						bill.Name = 'NameEsp'..Number
						bill.ExtentsOffset = Vector3.new(0, 1, 0)
						bill.Size = UDim2.new(1,200,1,30)
						bill.Adornee = v.Handle
						bill.AlwaysOnTop = true
						local name = Instance.new('TextLabel',bill)
						name.Font = Enum.Font.GothamSemibold
						name.FontSize = "Size14"
						name.TextWrapped = true
						name.Size = UDim2.new(1,0,1,0)
						name.TextYAlignment = 'Top'
						name.BackgroundTransparency = 1
						name.TextStrokeTransparency = 0.5
						name.TextColor3 = Color3.fromRGB(255, 255, 255)
						name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
					else
						v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
					end
				end
			else
				if v.Handle:FindFirstChild('NameEsp'..Number) then
					v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
				end
			end
		end)
	end
end
function UpdateFlowerChams() 
	for i,v in pairs(game.Workspace:GetChildren()) do
		pcall(function()
			if v.Name == "Flower2" or v.Name == "Flower1" then
				if FlowerESP then 
					if not v:FindFirstChild('NameEsp'..Number) then
						local bill = Instance.new('BillboardGui',v)
						bill.Name = 'NameEsp'..Number
						bill.ExtentsOffset = Vector3.new(0, 1, 0)
						bill.Size = UDim2.new(1,200,1,30)
						bill.Adornee = v
						bill.AlwaysOnTop = true
						local name = Instance.new('TextLabel',bill)
						name.Font = Enum.Font.GothamSemibold
						name.FontSize = "Size14"
						name.TextWrapped = true
						name.Size = UDim2.new(1,0,1,0)
						name.TextYAlignment = 'Top'
						name.BackgroundTransparency = 1
						name.TextStrokeTransparency = 0.5
						name.TextColor3 = Color3.fromRGB(255, 0, 0)
						if v.Name == "Flower1" then 
							name.Text = ("Blue Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							name.TextColor3 = Color3.fromRGB(0, 0, 255)
						end
						if v.Name == "Flower2" then
							name.Text = ("Red Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
							name.TextColor3 = Color3.fromRGB(255, 0, 0)
						end
					else
						v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')
					end
				else
					if v:FindFirstChild('NameEsp'..Number) then
					v:FindFirstChild('NameEsp'..Number):Destroy()
					end
				end
			end   
		end)
	end
end
function UpdateRealFruitChams() 
	for i,v in pairs(game.Workspace.AppleSpawner:GetChildren()) do
		if v:IsA("Tool") then
			if RealFruitESP then 
				if not v.Handle:FindFirstChild('NameEsp'..Number) then
					local bill = Instance.new('BillboardGui',v.Handle)
					bill.Name = 'NameEsp'..Number
					bill.ExtentsOffset = Vector3.new(0, 1, 0)
					bill.Size = UDim2.new(1,200,1,30)
					bill.Adornee = v.Handle
					bill.AlwaysOnTop = true
					local name = Instance.new('TextLabel',bill)
					name.Font = Enum.Font.GothamSemibold
					name.FontSize = "Size14"
					name.TextWrapped = true
					name.Size = UDim2.new(1,0,1,0)
					name.TextYAlignment = 'Top'
					name.BackgroundTransparency = 1
					name.TextStrokeTransparency = 0.5
					name.TextColor3 = Color3.fromRGB(255, 0, 0)
					name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				else
					v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				end
			else
				if v.Handle:FindFirstChild('NameEsp'..Number) then
					v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
				end
			end 
		end
	end
	for i,v in pairs(game.Workspace.PineappleSpawner:GetChildren()) do
		if v:IsA("Tool") then
			if RealFruitESP then 
				if not v.Handle:FindFirstChild('NameEsp'..Number) then
					local bill = Instance.new('BillboardGui',v.Handle)
					bill.Name = 'NameEsp'..Number
					bill.ExtentsOffset = Vector3.new(0, 1, 0)
					bill.Size = UDim2.new(1,200,1,30)
					bill.Adornee = v.Handle
					bill.AlwaysOnTop = true
					local name = Instance.new('TextLabel',bill)
					name.Font = Enum.Font.GothamSemibold
					name.FontSize = "Size14"
					name.TextWrapped = true
					name.Size = UDim2.new(1,0,1,0)
					name.TextYAlignment = 'Top'
					name.BackgroundTransparency = 1
					name.TextStrokeTransparency = 0.5
					name.TextColor3 = Color3.fromRGB(255, 174, 0)
					name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				else
					v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				end
			else
				if v.Handle:FindFirstChild('NameEsp'..Number) then
					v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
				end
			end 
		end
	end
		for i,v in pairs(game.Workspace.BananaSpawner:GetChildren()) do
		if v:IsA("Tool") then
			if RealFruitESP then 
				if not v.Handle:FindFirstChild('NameEsp'..Number) then
					local bill = Instance.new('BillboardGui',v.Handle)
					bill.Name = 'NameEsp'..Number
					bill.ExtentsOffset = Vector3.new(0, 1, 0)
					bill.Size = UDim2.new(1,200,1,30)
					bill.Adornee = v.Handle
					bill.AlwaysOnTop = true
					local name = Instance.new('TextLabel',bill)
					name.Font = Enum.Font.GothamSemibold
					name.FontSize = "Size14"
					name.TextWrapped = true
					name.Size = UDim2.new(1,0,1,0)
					name.TextYAlignment = 'Top'
					name.BackgroundTransparency = 1
					name.TextStrokeTransparency = 0.5
					name.TextColor3 = Color3.fromRGB(251, 255, 0)
					name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				else
					v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')
				end
			else
				if v.Handle:FindFirstChild('NameEsp'..Number) then
					v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
				end
			end 
		end
	end
end

spawn(function()
    while wait() do
        pcall(function()
            if MobESP then
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if v:FindFirstChild('HumanoidRootPart') then
                        if not v:FindFirstChild("MobEap") then
                            local BillboardGui = Instance.new("BillboardGui")
                            local TextLabel = Instance.new("TextLabel")

                            BillboardGui.Parent = v
                            BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
                            BillboardGui.Active = true
                            BillboardGui.Name = "MobEap"
                            BillboardGui.AlwaysOnTop = true
                            BillboardGui.LightInfluence = 1.000
                            BillboardGui.Size = UDim2.new(0, 200, 0, 50)
                            BillboardGui.StudsOffset = Vector3.new(0, 2.5, 0)

                            TextLabel.Parent = BillboardGui
                            TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
                            TextLabel.BackgroundTransparency = 1.000
                            TextLabel.Size = UDim2.new(0, 200, 0, 50)
                            TextLabel.Font = Enum.Font.GothamBold
                            TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)
                            TextLabel.Text.Size = 35
                        end
                        local Dis = math.floor((game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).Magnitude)
                        v.MobEap.TextLabel.Text = v.Name.." - "..Dis.." Distance"
                    end
                end
            else
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if v:FindFirstChild("MobEap") then
                        v.MobEap:Destroy()
                    end
                end
            end
        end)
    end
end)

spawn(function()
    while wait() do
        pcall(function()
            if SeaESP then
                for i,v in pairs(game:GetService("Workspace").SeaBeasts:GetChildren()) do
                    if v:FindFirstChild('HumanoidRootPart') then
                        if not v:FindFirstChild("Seaesps") then
                            local BillboardGui = Instance.new("BillboardGui")
                            local TextLabel = Instance.new("TextLabel")

                            BillboardGui.Parent = v
                            BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
                            BillboardGui.Active = true
                            BillboardGui.Name = "Seaesps"
                            BillboardGui.AlwaysOnTop = true
                            BillboardGui.LightInfluence = 1.000
                            BillboardGui.Size = UDim2.new(0, 200, 0, 50)
                            BillboardGui.StudsOffset = Vector3.new(0, 2.5, 0)

                            TextLabel.Parent = BillboardGui
                            TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
                            TextLabel.BackgroundTransparency = 1.000
                            TextLabel.Size = UDim2.new(0, 200, 0, 50)
                            TextLabel.Font = Enum.Font.GothamBold
                            TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)
                            TextLabel.Text.Size = 35
                        end
                        local Dis = math.floor((game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).Magnitude)
                        v.Seaesps.TextLabel.Text = v.Name.." - "..Dis.." Distance"
                    end
                end
            else
                for i,v in pairs (game:GetService("Workspace").SeaBeasts:GetChildren()) do
                    if v:FindFirstChild("Seaesps") then
                        v.Seaesps:Destroy()
                    end
                end
            end
        end)
    end
end)

spawn(function()
    while wait() do
        pcall(function()
            if NpcESP then
                for i,v in pairs(game:GetService("Workspace").NPCs:GetChildren()) do
                    if v:FindFirstChild('HumanoidRootPart') then
                        if not v:FindFirstChild("NpcEspes") then
                            local BillboardGui = Instance.new("BillboardGui")
                            local TextLabel = Instance.new("TextLabel")

                            BillboardGui.Parent = v
                            BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
                            BillboardGui.Active = true
                            BillboardGui.Name = "NpcEspes"
                            BillboardGui.AlwaysOnTop = true
                            BillboardGui.LightInfluence = 1.000
                            BillboardGui.Size = UDim2.new(0, 200, 0, 50)
                            BillboardGui.StudsOffset = Vector3.new(0, 2.5, 0)

                            TextLabel.Parent = BillboardGui
                            TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
                            TextLabel.BackgroundTransparency = 1.000
                            TextLabel.Size = UDim2.new(0, 200, 0, 50)
                            TextLabel.Font = Enum.Font.GothamBold
                            TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)
                            TextLabel.Text.Size = 35
                        end
                        local Dis = math.floor((game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).Magnitude)
                        v.NpcEspes.TextLabel.Text = v.Name.." - "..Dis.." Distance"
                    end
                end
            else
                for i,v in pairs (game:GetService("Workspace").NPCs:GetChildren()) do
                    if v:FindFirstChild("NpcEspes") then
                        v.NpcEspes:Destroy()
                    end
                end
            end
        end)
    end
end)

function isnil(thing)
    return (thing == nil)
end
local function round(n)
    return math.floor(tonumber(n) + 0.5)
end
Number = math.random(1, 1000000)

function UpdateIslandMirageESP() 
    for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do
        pcall(function()
            if MirageIslandESP then 
                if v.Name == "Mirage Island" then
                    if not v:FindFirstChild('NameEsp') then
                        local bill = Instance.new('BillboardGui',v)
                        bill.Name = 'NameEsp'
                        bill.ExtentsOffset = Vector3.new(0, 1, 0)
                        bill.Size = UDim2.new(1,200,1,30)
                        bill.Adornee = v
                        bill.AlwaysOnTop = true
                        local name = Instance.new('TextLabel',bill)
                        name.Font = "Code"
                        name.FontSize = "Size14"
                        name.TextWrapped = true
                        name.Size = UDim2.new(1,0,1,0)
                        name.TextYAlignment = 'Top'
                        name.BackgroundTransparency = 1
                        name.TextStrokeTransparency = 0.5
                        name.TextColor3 = Color3.fromRGB(80, 245, 245)
                    else
                        v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                    end
                end
            else
                if v:FindFirstChild('NameEsp') then
                    v:FindFirstChild('NameEsp'):Destroy()
                end
            end
        end)
    end
end

function isnil(thing)
    return (thing == nil)
end
local function round(n)
    return math.floor(tonumber(n) + 0.5)
end
Number = math.random(1, 1000000)

function UpdateAfdESP() 
    for i,v in pairs(game:GetService("Workspace").NPCs:GetChildren()) do
        pcall(function()
            if AfdESP then 
                if v.Name == "Advanced Fruit Dealer" then
                    if not v:FindFirstChild('NameEsp') then
                        local bill = Instance.new('BillboardGui',v)
                        bill.Name = 'NameEsp'
                        bill.ExtentsOffset = Vector3.new(0, 1, 0)
                        bill.Size = UDim2.new(1,200,1,30)
                        bill.Adornee = v
                        bill.AlwaysOnTop = true
                        local name = Instance.new('TextLabel',bill)
                        name.Font = "Code"
                        name.FontSize = "Size14"
                        name.TextWrapped = true
                        name.Size = UDim2.new(1,0,1,0)
                        name.TextYAlignment = 'Top'
                        name.BackgroundTransparency = 1
                        name.TextStrokeTransparency = 0.5
                        name.TextColor3 = Color3.fromRGB(80, 245, 245)
                    else
                        v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                    end
                end
            else
                if v:FindFirstChild('NameEsp') then
                    v:FindFirstChild('NameEsp'):Destroy()
                end
            end
        end)
    end
end
    

    
    function InfAb()
        if InfAbility then
            if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility") then
                local inf = Instance.new("ParticleEmitter")
                inf.Acceleration = Vector3.new(0,0,0)
                inf.Archivable = true
                inf.Drag = 20
                inf.EmissionDirection = Enum.NormalId.Top
                inf.Enabled = true
                inf.Lifetime = NumberRange.new(0,0)
                inf.LightInfluence = 0
                inf.LockedToPart = true
                inf.Name = "Agility"
                inf.Rate = 500
                local numberKeypoints2 = {
                    NumberSequenceKeypoint.new(0, 0);
                    NumberSequenceKeypoint.new(1, 4); 
                }
                inf.Size = NumberSequence.new(numberKeypoints2)
                inf.RotSpeed = NumberRange.new(9999, 99999)
                inf.Rotation = NumberRange.new(0, 0)
                inf.Speed = NumberRange.new(30, 30)
                inf.SpreadAngle = Vector2.new(0,0,0,0)
                inf.Texture = ""
                inf.VelocityInheritance = 0
                inf.ZOffset = 2
                inf.Transparency = NumberSequence.new(0)
                inf.Color = ColorSequence.new(Color3.fromRGB(0,0,0),Color3.fromRGB(0,0,0))
                inf.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
            end
        else
            if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility") then
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility"):Destroy()
            end
        end
    end
    
    local LocalPlayer = game:GetService'Players'.LocalPlayer
    local originalstam = LocalPlayer.Character.Energy.Value
    function infinitestam()
        LocalPlayer.Character.Energy.Changed:connect(function()
            if InfiniteEnergy then
                LocalPlayer.Character.Energy.Value = originalstam
            end 
        end)
    end
    
    spawn(function()
        pcall(function()
            while wait(.1) do
                if InfiniteEnergy then
                    wait(0.1)
                    originalstam = LocalPlayer.Character.Energy.Value
                    infinitestam()
                end
            end
        end)
    end)
    
    function NoDodgeCool()
        if nododgecool then
            for i,v in next, getgc() do
                if game:GetService("Players").LocalPlayer.Character.Dodge then
                    if typeof(v) == "function" and getfenv(v).script == game:GetService("Players").LocalPlayer.Character.Dodge then
                        for i2,v2 in next, getupvalues(v) do
                            if tostring(v2) == "0.1" then
                            repeat wait(.1)
                                setupvalue(v,i2,0)
                            until not nododgecool
                            end
                        end
                    end
                end
            end
        end
    end
    
    function fly()
        local mouse=game:GetService("Players").LocalPlayer:GetMouse''
        localplayer=game:GetService("Players").LocalPlayer
        game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart")
        local torso = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
        local speedSET=25
        local keys={a=false,d=false,w=false,s=false}
        local e1
        local e2
        local function start()
            local pos = Instance.new("BodyPosition",torso)
            local gyro = Instance.new("BodyGyro",torso)
            pos.Name="EPIXPOS"
            pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
            pos.position = torso.Position
            gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
            gyro.CFrame = torso.CFrame
            repeat
                    wait()
                    localplayer.Character.Humanoid.PlatformStand=true
                    local new=gyro.CFrame - gyro.CFrame.p + pos.position
                    if not keys.w and not keys.s and not keys.a and not keys.d then
                    speed=1
                    end
                    if keys.w then
                    new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
                    speed=speed+speedSET
                    end
                    if keys.s then
                    new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
                    speed=speed+speedSET
                    end
                    if keys.d then
                    new = new * CFrame.new(speed,0,0)
                    speed=speed+speedSET
                    end
                    if keys.a then
                    new = new * CFrame.new(-speed,0,0)
                    speed=speed+speedSET
                    end
                    if speed>speedSET then
                    speed=speedSET
                    end
                    pos.position=new.p
                    if keys.w then
                    gyro.CFrame = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*15),0,0)
                    elseif keys.s then
                    gyro.CFrame = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*15),0,0)
                    else
                    gyro.CFrame = workspace.CurrentCamera.CoordinateFrame
                    end
            until not Fly
            if gyro then 
                    gyro:Destroy() 
            end
            if pos then 
                    pos:Destroy() 
            end
            flying=false
            localplayer.Character.Humanoid.PlatformStand=false
            speed=0
        end
        e1=mouse.KeyDown:connect(function(key)
            if not torso or not torso.Parent then 
                    flying=false e1:disconnect() e2:disconnect() return 
            end
            if key=="w" then
                keys.w=true
            elseif key=="s" then
                keys.s=true
            elseif key=="a" then
                keys.a=true
            elseif key=="d" then
                keys.d=true
            end
        end)
        e2=mouse.KeyUp:connect(function(key)
            if key=="w" then
                keys.w=false
            elseif key=="s" then
                keys.s=false
            elseif key=="a" then
                keys.a=false
            elseif key=="d" then
                keys.d=false
            end
        end)
        start()
    end
    
    function Click()
        game:GetService'VirtualUser':CaptureController()
        game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
    end
    
    function AutoHaki()
        if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("HasBuso") then
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
        end
    end
    
    function UnEquipWeapon(Weapon)
        if game.Players.LocalPlayer.Character:FindFirstChild(Weapon) then
            _G.NotAutoEquip = true
            wait(.5)
            game.Players.LocalPlayer.Character:FindFirstChild(Weapon).Parent = game.Players.LocalPlayer.Backpack
            wait(.1)
            _G.NotAutoEquip = false
        end
    end
    
    function EquipWeapon(ToolSe)
        if not _G.NotAutoEquip then
            if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
                Tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
                wait(.1)
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tool)
            end
        end
    end
    
    spawn(function()
	while wait() do
		for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"]:GetChildren()) do
			pcall(function()
				if v.Name == ("CurvedRing") or v.Name == ("SlashHit") or v.Name == ("SwordSlash") or v.Name == ("SlashTail") or v.Name == ("Sounds") then
					v:Destroy()
				end
			end)
		end
	end
    end)
    
    function GetDistance(target)
        return math.floor((target.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude)
    end
    
    function BTP(P)
	repeat wait(1)
		game.Players.LocalPlayer.Character.Humanoid:ChangeState(15)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
		task.wait()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
	until (P.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1500
end

function TelePPlayer(P)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
end
    
    function TP(Pos)
    Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 25 then
        Speed = 10000
    elseif Distance < 50 then
        Speed = 2000
    elseif Distance < 150 then
        Speed = 800
    elseif Distance < 250 then
        Speed = 600
    elseif Distance < 500 then
        Speed = 400
    elseif Distance < 750 then
        Speed = 250
    elseif Distance >= 1000 then
        Speed = 200
    end
    game:GetService("TweenService"):Create(
        game.Players.LocalPlayer.Character.HumanoidRootPart,
        TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
        {CFrame = Pos}
    ):Play()
end

    function TP1(Pos)
        Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        if Distance < 25 then
            Speed = 5000
        elseif Distance < 50 then
            Speed = 2000
        elseif Distance < 150 then
            Speed = 800
        elseif Distance < 250 then
            Speed = 600
        elseif Distance < 500 then
            Speed = 300
        elseif Distance < 750 then
            Speed = 250
        elseif Distance >= 1000 then
            Speed = 200
        end
        game:GetService("TweenService"):Create(
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
            {CFrame = Pos}
        ):Play()
end
function TP2(Pos)
    Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 25 then
        Speed = 50
    elseif Distance < 50 then
        Speed = 20
    elseif Distance < 150 then
        Speed = 80
    elseif Distance < 250 then
        Speed = 60
    elseif Distance < 500 then
        Speed = 30
    elseif Distance < 750 then
        Speed = 25
    elseif Distance >= 1000 then
        Speed = 20
    end
    game:GetService("TweenService"):Create(
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
        TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
        {CFrame = Pos}
    ):Play()
end
    function topos(Pos)
        Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        if Distance < 25 then
            Speed = 5000
        elseif Distance < 50 then
            Speed = 2000
        elseif Distance < 150 then
            Speed = 800
        elseif Distance < 250 then
            Speed = 600
        elseif Distance < 500 then
            Speed = 300
        elseif Distance < 750 then
            Speed = 250
        elseif Distance >= 1000 then
            Speed = 200
        end
        game:GetService("TweenService"):Create(
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
            {CFrame = Pos}
        ):Play()
end

function TPB(CFgo)
	local tween_s = game:service"TweenService"
	local info = TweenInfo.new((game:GetService("Workspace").Boats.MarineBrigade.VehicleSeat.CFrame.Position - CFgo.Position).Magnitude/300, Enum.EasingStyle.Linear)
	tween = tween_s:Create(game:GetService("Workspace").Boats.MarineBrigade.VehicleSeat, info, {CFrame = CFgo})
	tween:Play()

	local tweenfunc = {}

	function tweenfunc:Stop()
		tween:Cancel()
	end

	return tweenfunc
end

function TPP(CFgo)
	if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health <= 0 or not game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") then tween:Cancel() repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") and game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 wait(7) return end
	local tween_s = game:service"TweenService"
	local info = TweenInfo.new((game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - CFgo.Position).Magnitude/325, Enum.EasingStyle.Linear)
	tween = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = CFgo})
	tween:Play()

	local tweenfunc = {}

	function tweenfunc:Stop()
		tween:Cancel()
	end

	return tweenfunc
end

getgenv().ToTargets = function(p)
    task.spawn(function()
        pcall(function()
            if game:GetService("Players").LocalPlayer:DistanceFromCharacter(p.Position) <= 250 then 
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = p
            elseif not game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
                local K = Instance.new("Part",game.Players.LocalPlayer.Character)
                K.Size = Vector3.new(1,0.5,1)
                K.Name = "Root"
                K.Anchored = true
                K.Transparency = 1
                K.CanCollide = false
                K.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,20,0)
            end
            local U = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude
            local z = game:service("TweenService")
            local B = TweenInfo.new((p.Position-game.Players.LocalPlayer.Character.Root.Position).Magnitude/300,Enum.EasingStyle.Linear)
            local S,g = pcall(function()
            local q = z:Create(game.Players.LocalPlayer.Character.Root,B,{CFrame = p})
            q:Play()
        end)
        if not S then 
            return g
        end
        game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
            if S and game.Players.LocalPlayer.Character:FindFirstChild("Root") then 
                pcall(function()
                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 20 then 
                        spawn(function()
                            pcall(function()
                                if (game.Players.LocalPlayer.Character.Root.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 150 then 
                                    game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                                else 
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=game.Players.LocalPlayer.Character.Root.CFrame
                                end
                            end)
                        end)
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 10 and(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 20 then 
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 10 then 
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p
                    end
                end)
            end
	    end)
    end)
    end
    
    spawn(function()
    game:GetService("RunService").Heartbeat:Connect(function()
        if _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFactory or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.AutoFarmBone or _G.Autoheart or _G.Autodoughking or _G.AutoFarmMaterial or _G.AutoNevaSoulGuitar or _G.Auto_Dragon_Trident or _G.Autotushita or _G.d or _G.Autowaden or _G.Autogay or _G.Autopole or _G.Autosaw or _G.AutoObservationHakiV2 or _G.AutoFarmNearest or AutoFarmChest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Tweenfruit or _G.AutoKai or _G.TeleportNPC or _G.Leather or _G.Auto_Wing or _G.Umm or _G.Makori_gay or Radioactive or Fish or Gunpowder or Dragon_Scale or Cocoafarm or Scrap or MiniHee or _G.AutoFarmSeabaest or Auto_Cursed_Dual_Katana or _G.AutoFarmMob or _G.AutoMysticIsland or _G.AutoFarmDungeon or _G.AutoRaidPirate or _G.AutoQuestRace or _G.TweenMGear or getgenv().AutoFarm or _G.AutoPlayerHunter or _G.AutoFactory or Grab_Chest or _G.Namfon or _G.AutoSwordMastery or _G.AutoSeaBest or _G.AutoKillTial then
            if not game:GetService("Workspace"):FindFirstChild("LOL") then
                local LOL = Instance.new("Part")
                LOL.Name = "LOL"
                LOL.Parent = game.Workspace
                LOL.Anchored = true
                LOL.Transparency = 1
                LOL.Size = Vector3.new(30,-0.5,30)
            elseif game:GetService("Workspace"):FindFirstChild("LOL") then
                game.Workspace["LOL"].CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0, -3.6, 0)
            end
        else
            if game:GetService("Workspace"):FindFirstChild("LOL") then
                game:GetService("Workspace"):FindFirstChild("LOL"):Destroy()
            end
        end
    end)
    end)

    spawn(function()
        pcall(function()
            while wait() do
                if _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFactory or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.AutoFarm or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.AutoFarmBone or _G.Autoheart or _G.Autodoughking or _G.AutoFarmMaterial or _G.AutoNevaSoulGuitar or _G.Auto_Dragon_Trident or _G.Autotushita or _G.d or _G.Autowaden or _G.Autogay or _G.Autopole or _G.Autosaw or _G.AutoObservationHakiV2 or _G.AutoFarmNearest or AutoFarmChest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Tweenfruit or _G.TeleportNPC or _G.Leather or _G.Auto_Wing or _G.Umm or _G.Makori_gay or Radioactive or Fish or Gunpowder or Dragon_Scale or Cocoafarm or Scrap or MiniHee or _G.AutoFarmSeabaest or Auto_Cursed_Dual_Katana or _G.AutoFarmMob or _G.AutoMysticIsland or _G.AutoFarmDungeon or _G.AutoRaidPirate or _G.AutoQuestRace or _G.TweenMGear or getgenv().AutoFarm or _G.AutoPlayerHunter or _G.AutoFactory or Grab_Chest or _G.Namfon or _G.AutoSwordMastery or _G.Auto_Seabest or _G.AutoSeaBest or _G.AutoKillTial == true then
                    if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                        local Noclip = Instance.new("BodyVelocity")
                        Noclip.Name = "BodyClip"
                        Noclip.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                        Noclip.MaxForce = Vector3.new(100000,100000,100000)
                        Noclip.Velocity = Vector3.new(0,0,0)
                    end
                end
            end
        end)
    end)
    
    spawn(function()
        pcall(function()
            game:GetService("RunService").Stepped:Connect(function()
                if _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFactory or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.AutoFarmBone or _G.Autoheart or _G.Autodoughking or _G.AutoFarmMaterial or _G.AutoNevaSoulGuitar or _G.Auto_Dragon_Trident or _G.Autotushita or _G.Autowaden or _G.Autogay or _G.Autopole or _G.Autosaw or _G.AutoObservationHakiV2 or _G.AutoFarmNearest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Tweenfruit or _G.TeleportNPC or _G.AutoKai or _G.Leather or _G.Auto_Wing or _G.Umm or _G.Makori_gay or Radioactive or Fish or Gunpowder or Dragon_Scale or Cocoafarm or Scrap or MiniHee or _G.AutoFarmSeabaest or Auto_Cursed_Dual_Katana or _G.AutoFarmMob or _G.AutoMysticIsland or _G.AutoFarmDungeon or _G.AutoRaidPirate or _G.AutoQuestRace or _G.TweenMGear or getgenv().AutoFarm or _G.AutoPlayerHunter or _G.AutoFactory or _G.Namfon or _G.AutoSwordMastery or _G.Auto_Seabest or _G.AutoSeaBest or _G.AutoKillTial == true then
                    for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do
                        if v:IsA("BasePart") then
                            v.CanCollide = false    
                        end
                    end
                end
            end)
        end)
    end)
    
    function TP3(pos)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
    end
    
    spawn(function()
        while wait() do
            if _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFactory or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.AutoFarmBone or _G.Autoheart or _G.Autodoughking or _G.d or _G.Autowaden or _G.Autogay or _G.AutoObservationHakiV2 or _G.AutoFarmMaterial or _G.AutoFarmNearest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Leather or _G.Auto_Wing or _G.Umm or _G.Makori_gay or Radioactive or Fish or Gunpowder or Dragon_Scale or Cocoafarm or Scrap or MiniHee or _G.AutoFarmSeabaest or Auto_Cursed_Dual_Katana or _G.AutoFarmMob or _G.AutoRaidPirate or getgenv().AutoFarm or _G.AutoPlayerHunter or _G.AutoFactory or _G.AttackDummy or _G.AutoSwordMastery or _G.Auto_Seabest or _G.AutoSeaBest or _G.AutoKillTial == true then
                pcall(function()
                    game:GetService("ReplicatedStorage").Remotes.CommE:FireServer("Ken",true)
                end)
            end    
        end
    end)
    
    spawn(function()
    game:GetService("RunService").RenderStepped:Connect(function()
        if _G.AutoClick or Fastattack then
             pcall(function()
                game:GetService'VirtualUser':CaptureController()
			    game:GetService'VirtualUser':Button1Down(Vector2.new(0,1,0,1))
            end)
        end
    end)
   end)

    function StopTween(target)
        if not target then
            _G.StopTween = true
            wait()
            topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
            wait()
            if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()
            end
            _G.StopTween = false
            _G.Clip = false
        end
    end
    
    spawn(function()
        pcall(function()
            while wait() do
                for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do  
                    if v:IsA("Tool") then
                        if v:FindFirstChild("RemoteFunctionShoot") then 
                            SelectWeaponGun = v.Name
                        end
                    end
                end
            end
        end)
    end)
    
    game:GetService("Players").LocalPlayer.Idled:connect(function()
        game:GetService("VirtualUser"):Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
        wait(1)
        game:GetService("VirtualUser"):Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
    end)

local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()
local window = DrRayLibrary:Load("Questy Hub", "Default")
local General = DrRayLibrary.newTab("General", "6026568198")
local Stats = DrRayLibrary.newTab("Stats", "7040410130")
local Teleport = DrRayLibrary.newTab("Teleport", "6035190846")
local Dungeon = DrRayLibrary.newTab("Dungeon", "7044284832")
local Shop = DrRayLibrary.newTab("Shop", "6031265976")
local DevilFruit = DrRayLibrary.newTab("Fruit", "7044233235")
local ESP = DrRayLibrary.newTab("ESP", "12950874071")
local Misc = DrRayLibrary.newTab("Misc", "6034509993")

General.newToggle("Start Auto Farm Level", "เริ่มออโต้ฟาร์มเลเวล", _G.Auto_Farm_Level, function(value)
 _G.Auto_Farm_Level = value 
 _G.AutoFarmLv = value
	   _G.BringMonster = value
_G.AUTOHAKI = value
_G.Point = 99999999999999
end)

spawn(function()
    game:GetService("RunService").RenderStepped:Connect(function()
        if _G.Remove_trct == true then
            game:GetService("ReplicatedStorage").Notification:Destroy()        
        end
    end)
end)
spawn(function()
    game:GetService("RunService").RenderStepped:Connect(function()
        if _G.RemoveHit == true then
            game:GetService("ReplicatedStorage").Effect.Container.LevelUp:Destroy()
            game:GetService("ReplicatedStorage").Util.Sound:Destroy()
            game:GetService("ReplicatedStorage").Util.Sound.Storage.Other:FindFirstChild("LevelUp_Proxy"):Destroy()
            game:GetService("ReplicatedStorage").Util.Sound.Storage.Other:FindFirstChild("LevelUp"):Destroy()
            game:GetService("ReplicatedStorage").Effect.Container.Respawn:Destroy()        
        end
    end)
end)
spawn(function()
    while wait(.1) do
        if _G.AUTOHAKI then 
            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                local args = {
                    [1] = "Buso"
                }
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end
        end
    end
end)
spawn(function()
	while wait() do
		if getgenv().remove then
			pcall(function()
			game.ReplicatedStorage.Effect.Container.Death:Destroy()
			game.ReplicatedStorage.Effect.Container.Respawn:Destroy()
			game.ReplicatedStorage.Effect.Container.Hit:Destroy()                    end)
			end
			end
			end)
spawn(function()
	while wait() do
		if getgenv().removeheavy then
			pcall(function()
			game:GetService("ReplicatedStorage").Effect.Container:Destroy()
			game:GetService("ReplicatedStorage").Assets:FindFirstChild('SlashHit'):Destroy()
			end)
			end
			end
			end)

spawn(function()
	while task.wait() do
		pcall(function()
			if getgenv().DisnableDame then
				game:GetService("ReplicatedStorage").Assets.GUI.DamageCounter.Enabled = false
			else
				game:GetService("ReplicatedStorage").Assets.GUI.DamageCounter.Enabled = true
			end
		end)
	end
end)
function GetDistance(target)
    return math.floor((target.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude)
end
RandomCFrame = 0
spawn(function()  
    while task.wait() do --นี้
        pcall(function()
        if _G.Auto_Farm_Level then
            local MyLevel = game.Players.LocalPlayer.Data.Level.Value
            local QuestC = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest
            if _G.AutoFarmFast and (MyLevel >= 10 and MyLevel <= 300) then
              if MyLevel >= 10 and MyLevel <= 69 then
                CFrameMon = CFrame.new(-4716.95703, 853.089722, -1933.92542, -0.93441087, -6.77488776e-09, -0.356197298, 1.12145182e-08, 1, -4.84390199e-08, 0.356197298, -4.92565206e-08, -0.93441087)
                BringMobFarm = false
                for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                    if v.Name == "God's Guard [Lv. 450]" then
                        if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                            repeat task.wait()
                                EquipWeapon(_G.SelectWeapon)
                                getgenv().noclip = true
                                _G.AutoFarmLv = false
                                v.HumanoidRootPart.CanCollide = false
                                v.Humanoid.WalkSpeed = 0
                                v.Head.CanCollide = false
                                BringMobFarm = true
                                PosMon = v.HumanoidRootPart.CFrame
                                v.HumanoidRootPart.Size = Vector3.new(100,100,100)
                                v.HumanoidRootPart.Transparency = 1
                                spawn(function()
                                    if RandomCFrame <= 1 then
                                        topos(v.HumanoidRootPart.CFrame * CFrame.new(0,20,50))
                                        RandomCFrame = RandomCFrame + 0.1
                                    elseif RandomCFrame >= 1 and RandomCFrame <= 2 then
                                        topos(v.HumanoidRootPart.CFrame * CFrame.new(50,20,0))
                                        RandomCFrame = RandomCFrame + 0.1
                                    elseif RandomCFrame >= 2 and RandomCFrame <= 3 then
                                        topos(v.HumanoidRootPart.CFrame *CFrame.new(0,20,-50))
                                        RandomCFrame = RandomCFrame + 0.1
                                    elseif RandomCFrame >= 3 and RandomCFrame <= 4  then
                                        topos(v.HumanoidRootPart.CFrame * CFrame.new(-50,20,0))
                                        RandomCFrame = RandomCFrame + 0.1
                                    elseif RandomCFrame >=4 and RandomCFrame <= 5 then
                                        topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                        RandomCFrame = 0
                                    end
                                end)
                                game:GetService'VirtualUser':CaptureController()
                                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                            until not _G.Auto_Farm_Level  or not v.Parent or v.Humanoid.Health <= 0
                        end
                    end
                end
                for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do 
                    if v.Name == "God's Guard [Lv. 450]" then
                        getgenv().ToTarget(v.HumanoidRootPart.CFrame * CFrame.new(0,35,5))
                     else
                         _G.AutoFarmLv = false
                         BringMobFarm = false
                         getgenv().noclip = false
                        CFrameMon = CFrame.new(-4716.95703, 853.089722, -1933.92542, -0.93441087, -6.77488776e-09, -0.356197298, 1.12145182e-08, 1, -4.84390199e-08, 0.356197298, -4.92565206e-08, -0.93441087)
                        getgenv().ToTarget(CFrameMon)
                        if _G.Auto_Farm_Level and (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
                            end
                        end
                   end
                elseif MyLevel >= 70 and MyLevel <= 310 then
                    if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                     end
                    if QuestC.Visible == false then
                    CFrameMon = CFrame.new(-4716.95703, 853.089722, -1933.92542, -0.93441087, -6.77488776e-09, -0.356197298, 1.12145182e-08, 1, -4.84390199e-08, 0.356197298, -4.92565206e-08, -0.93441087)
                     BringMobFarm = false
                     for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                         if v.Name == "God's Guard [Lv. 450]" then
                             if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                 repeat task.wait()
                                     EquipWeapon(_G.SelectWeapon)
                                     getgenv().noclip = true
                                     _G.AutoFarmLv = true
                                     v.HumanoidRootPart.CanCollide = false
                                     v.Humanoid.WalkSpeed = 0
                                     v.Head.CanCollide = false
                                     v.HumanoidRootPart.Size = Vector3.new(100,100,100)
                                     v.HumanoidRootPart.Transparency = 1
                                     BringMobFarm = true
                                     PosMon = v.HumanoidRootPart.CFrame
                                     spawn(function()
                                        if RandomCFrame <= 1 then
                                            topos(v.HumanoidRootPart.CFrame * CFrame.new(0,20,50))
                                            RandomCFrame = RandomCFrame + 0.1
                                        elseif RandomCFrame >= 1 and RandomCFrame <= 2 then
                                            topos(v.HumanoidRootPart.CFrame * CFrame.new(50,20,0))
                                            RandomCFrame = RandomCFrame + 0.1
                                        elseif RandomCFrame >= 2 and RandomCFrame <= 3 then
                                            topos(v.HumanoidRootPart.CFrame *CFrame.new(0,20,-50))
                                            RandomCFrame = RandomCFrame + 0.1
                                        elseif RandomCFrame >= 3 and RandomCFrame <= 4  then
                                            topos(v.HumanoidRootPart.CFrame * CFrame.new(-50,20,0))
                                            RandomCFrame = RandomCFrame + 0.1
                                        elseif RandomCFrame >=4 and RandomCFrame <= 5 then
                                            topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                            RandomCFrame = 0
                                        end
                                    end)
                                     game:GetService'VirtualUser':CaptureController()
                                     game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                 until not _G.Auto_Farm_Level  or not v.Parent or v.Humanoid.Health <= 0
                             end
                         end
                     end
                     for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do 
                         if v.Name == "God's Guard [Lv. 450]" then
                            spawn(function()
                                if RandomCFrame <= 1 then
                                    topos(v.HumanoidRootPart.CFrame * CFrame.new(0,20,50))
                                    RandomCFrame = RandomCFrame + 0.1
                                elseif RandomCFrame >= 1 and RandomCFrame <= 2 then
                                    topos(v.HumanoidRootPart.CFrame * CFrame.new(50,20,0))
                                    RandomCFrame = RandomCFrame + 0.1
                                elseif RandomCFrame >= 2 and RandomCFrame <= 3 then
                                    topos(v.HumanoidRootPart.CFrame *CFrame.new(0,20,-50))
                                    RandomCFrame = RandomCFrame + 0.1
                                elseif RandomCFrame >= 3 and RandomCFrame <= 4  then
                                    topos(v.HumanoidRootPart.CFrame * CFrame.new(-50,20,0))
                                    RandomCFrame = RandomCFrame + 0.1
                                elseif RandomCFrame >=4 and RandomCFrame <= 5 then
                                    topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                    RandomCFrame = 0
                                end
                            end)
                          else
                              _G.AutoFarmLv = true
                              BringMobFarm = false
                              getgenv().noclip = false
                             CFrameMon = CFrame.new(-4716.95703, 853.089722, -1933.92542, -0.93441087, -6.77488776e-09, -0.356197298, 1.12145182e-08, 1, -4.84390199e-08, 0.356197298, -4.92565206e-08, -0.93441087)
                             getgenv().ToTarget(CFrameMon)
                             if _G.Auto_Farm_Level and (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
                                     game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
                                 end
                             end
                        end
                   elseif QuestC.Visible == true then
                     _G.FastAttack = false
                     local quest = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text
                     local Player = string.split(quest," ")[2]
                      getgenv().SelectPly = string.split(quest," ")[2]
                      if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                         game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                         game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                         game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                         game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                         game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                         game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                     end
                      if string.find(quest,"Defeat") then
                         repeat task.wait()
                           if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                 game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                             end
                             game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible = false
                             game:GetService("Players").LocalPlayer.PlayerGui.Main.SafeZone.Visible = false
                             if game:GetService("Players").LocalPlayer.PlayerGui.Main.PvpDisabled.Visible == true then
                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EnablePvp")
                            end
                              EquipWeapon(_G.SelectWeapon)
                              TPPlayer(game:GetService("Players")[getgenv().SelectPly].Character.HumanoidRootPart.CFrame*CFrame.new(0,0,5))
                              game:GetService("VirtualUser"):CaptureController()
                              game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                              game.Players:FindFirstChild(Player).Character.HumanoidRootPart.Size = Vector3.new(120,120,120)
                              game:service('VirtualInputManager'):SendKeyEvent(true, "Z", false, game)
                              game:service('VirtualInputManager'):SendKeyEvent(false, "Z", false, game)
                              game:service('VirtualInputManager'):SendKeyEvent(true, "X", false, game)
                              game:service('VirtualInputManager'):SendKeyEvent(false, "X", false, game)
                         until game.Players:FindFirstChild(Player).Character.Humanoid.Health <= 0 or not game.Players:FindFirstChild(Player) or not FastFarm()
                             if not game.Players:FindFirstChild(Player) then
                                 game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                             end   
                        else
                             game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
                      end
                end
                elseif MyLevel >= 300 and MyLevel <= 2450 then
             if QuestC.Visible == false then
                _G.AutoFarmLv = true
            else
                    _G.AutoFarmLv = true
                    end
             else
                _G.AutoFarmLv = true
               end
          end
         if _G.AutoFarmLv then
                CheckQuest()
                if QuestC.Visible == false then
                    CheckQuest()
                    repeat wait() getgenv().ToTarget(CFrameMon) until (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30000 or not _G.Auto_Farm_Level
                    if (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30000 then
                        wait(.2)
                        BringMobFarm = false
                        getgenv().noclip = false
                        wait(.2)
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NameQuest,LevelQuest)
                        wait(0.5)
                        getgenv().ToTarget(CFrameMon)
                    end
                    elseif QuestC.Visible == true then
                    CheckQuest()
                    if game:GetService("Workspace").Enemies:FindFirstChild(Mon) then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                                if v.Name == Mon then
                                    if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                                        repeat game.RunService.Heartbeat:wait()
                                            EquipWeapon(_G.SelectWeapon)
                                            getgenv().noclip = true
        spawn(function()
    if RandomCFrame <= 1 then
        topos(v.HumanoidRootPart.CFrame * CFrame.new(0,20,50))
        RandomCFrame = RandomCFrame + 0.1
    elseif RandomCFrame >= 1 and RandomCFrame <= 2 then
        topos(v.HumanoidRootPart.CFrame * CFrame.new(50,20,0))
        RandomCFrame = RandomCFrame + 0.1
    elseif RandomCFrame >= 2 and RandomCFrame <= 3 then
        topos(v.HumanoidRootPart.CFrame *CFrame.new(0,20,-50))
        RandomCFrame = RandomCFrame + 0.1
    elseif RandomCFrame >= 3 and RandomCFrame <= 4  then
        topos(v.HumanoidRootPart.CFrame * CFrame.new(-50,20,0))
        RandomCFrame = RandomCFrame + 0.1
    elseif RandomCFrame >=4 and RandomCFrame <= 5 then
        topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
        RandomCFrame = 0
    end
end)
                                            v.HumanoidRootPart.CanCollide = false
                                            PosMon = v.HumanoidRootPart.CFrame
                                            v.Humanoid.WalkSpeed = 20
                                            v.Head.CanCollide = false
                                            _G.FastAttack = true
                                            BringMobFarm = true
                                            CheckMon = false
                                            v.HumanoidRootPart.Size = Vector3.new(100,100,100)
                                            v.HumanoidRootPart.Transparency = 1
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        until not _G.Auto_Farm_Level or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                    else
                                        CheckQuest()
                                        getgenv().ToTarget(CFrameMon)
                                    end
                                end
                                if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                                end
                            end
                        end
                    else
                        BringMobFarm = false
                        getgenv().noclip = false
                        if game:GetService("ReplicatedStorage"):FindFirstChild(Mon) then
                            getgenv().ToTarget(game:GetService("ReplicatedStorage"):FindFirstChild(Mon).HumanoidRootPart.CFrame * CFrame.new(5,10,7))
                               else
                                     getgenv().ToTarget(CFrameMon)
                                     getgenv().noclip = false
                                    end
                               end
                          end
                     end
                end
           end)
     end
 end)
 spawn(function()
    while true do wait()
        if setscriptable then
            setscriptable(game.Players.LocalPlayer, "SimulationRadius", true)
        end
        if sethiddenproperty then
            sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
        end
    end
end)
   spawn(function()
      while task.wait() do
            pcall(function()
                if _G.BringMonster and BringMobFarm then
                   for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                       if not string.find(v.Name,"Boss") and (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
                           if InMyNetWork(v.HumanoidRootPart) then
                               v.HumanoidRootPart.CFrame = PosMon
                               v.Humanoid.JumpPower = 0
                               v.Humanoid.WalkSpeed = 0
                               v.HumanoidRootPart.Size = Vector3.new(100,100,100)
                               v.HumanoidRootPart.Transparency = 1
                               v.HumanoidRootPart.CanCollide = false
                               v.Head.CanCollide = false
                               if v.Humanoid:FindFirstChild("Animator") then
                                   v.Humanoid.Animator:Destroy()
                               end
                                  v.Humanoid:ChangeState(11)
                                  v.Humanoid:ChangeState(14)
                              end
                          end
                      end
                 end
            end)
       end
 end)
                
function InMyNetWork(object)
    if isnetworkowner then
        return isnetworkowner(object)
    else
        if (object.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then 
            return true
        end
        return false
    end
end

spawn(function()
    while wait() do 
        if _G.StartKaitan then
            if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Death Step") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Death Step") then
                if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 450 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
                    _G.SelectWeapon = "Death Step"
                end  
                if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg") and game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 450 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
                    _G.SelectWeapon = "Death Step"
                end  
                if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 449 then
                    _G.SelectWeapon = "Black Leg"
                end 
            else 
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
            end
        end
    end
end)

General.newToggle("Start Auto Chest Fast", "เริ่มออโต้ฟาร์มหีเร็ว", _G.ChestBypass, function(value)
   _G.ChestBypass = value
end)

spawn(function()
	while wait() do
		if _G.ChestBypass then
			pcall(function()
				for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
					if string.find(v.Name, "Chest") then
						print(v.Name)
						game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame
						wait(.15)
					end
				end
				game.Players.LocalPlayer.Character.Head:Destroy()
				for _,v in pairs(game:GetService("Workspace"):GetDescendants()) do
					if string.find(v.Name, "Chest") and v:IsA("TouchTransmitter") then
						firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, v.Parent, 0) --0 is touch
						wait()
						firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, v.Parent, 1) -- 1 is untouch
					end
				end
			end)
		end
	end
end)

spawn(function()
	while task.wait() do
		if _G.ChestBypass then
			local ohString1 = "SetTeam"
			local ohString2 = "Pirates"
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(ohString1, ohString2)
		end
	end
end)

if World3 then

General.newToggle("Start Auto Farm Bone", "เริ่มออโต้ฟาร์มโบน ", _G.Auto_Farm_Bone, function(value)
      _G.Auto_Farm_Bone = value
	StopTween(_G.Auto_Farm_Bone)
end)

General.newToggle("Auto Random Bone ", "ออโต้สุ่มโบน", _G.Auto_Random_Bone, function(value)
  _G.Auto_Random_Bone = value
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.Auto_Random_Bone then    
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,1)
			end
		end
	end)
end)

if World3 then

General.newToggle("Start Auto Dought Boss", "ออโต้ฟาร์มบอสโมจิ ", _G.Auto_Cake_Prince, function(value)
  	_G.Auto_Cake_Prince = value
	StopTween(_G.Auto_Cake_Prince)
end)

spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function()
		pcall(function()
			for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
				if _G.Auto_Cake_Prince and StartCakeStartMagnet and (v.Name == "Cookie Crafter [Lv. 2200]" or v.Name == "Cake Guard [Lv. 2225]" or v.Name == "Baking Staff [Lv. 2250]" or v.Name == "Head Baker [Lv. 2275]") and (v.HumanoidRootPart.Position - POSCAKE.Position).magnitude <= 350 then
					v.HumanoidRootPart.CFrame = POSCAKE
					v.HumanoidRootPart.CanCollide = false
					v.HumanoidRootPart.Size = Vector3.new(50,50,50)
					if v.Humanoid:FindFirstChild("Animator") then
						v.Humanoid.Animator:Destroy()
					end
					sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
				end
			end
		end)
	end)
end)

spawn(function()
	while wait() do
		if _G.Auto_Cake_Prince then
			pcall(function()
				if game.ReplicatedStorage:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") then   
					if game:GetService("Workspace").Enemies:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do 
							if v.Name == "Cake Prince [Lv. 2300] [Raid Boss]" then
								repeat wait()
									AutoHaki()
									EquipWeapon(_G.Select_Weapon)
									v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
									v.HumanoidRootPart.CanCollide = false
									topos(v.HumanoidRootPart.CFrame * MethodFarm)
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								until _G.Auto_Cake_Prince == false or not v.Parent or v.Humanoid.Health <= 0
							end    
						end    
					else
						topos(CFrame.new(-2009.2802734375, 4532.97216796875, -14937.3076171875)) 
					end
				else
					if game.Workspace.Enemies:FindFirstChild("Baking Staff [Lv. 2250]") or game.Workspace.Enemies:FindFirstChild("Head Baker [Lv. 2275]") or game.Workspace.Enemies:FindFirstChild("Cake Guard [Lv. 2225]") or game.Workspace.Enemies:FindFirstChild("Cookie Crafter [Lv. 2200]")  then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do  
							if (v.Name == "Baking Staff [Lv. 2250]" or v.Name == "Head Baker [Lv. 2275]" or v.Name == "Cake Guard [Lv. 2225]" or v.Name == "Cookie Crafter [Lv. 2200]") and v.Humanoid.Health > 0 then
								repeat wait()
									AutoHaki()
									EquipWeapon(_G.Select_Weapon)
									StartCakeStartMagnet = true
									v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)  
									POSCAKE = v.HumanoidRootPart.CFrame
									topos(v.HumanoidRootPart.CFrame * MethodFarm)
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								until _G.Auto_Cake_Prince == false or game:GetService("ReplicatedStorage"):FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") or not v.Parent or v.Humanoid.Health <= 0
							end
						end
					else
						StartCakeStartMagnet = false
						topos(CFrame.new(-1820.0634765625, 210.74781799316406, -12297.49609375))
					end
				end
			end)
		end
	end
end)

General.newToggle("Auto Open Dought Boss ", "ออโต้เสกบอสโมจิ ", _G.Auto_Open_Dough_Dungeon, function(value)
  _G.Auto_Open_Dough_Dungeon = value
	StopTween(_G.Auto_Open_Dough_Dungeon)
end)

spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function()
		pcall(function()
			for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
				if _G.Auto_Open_Dough_Dungeon and StartCakeStartMagnet and (v.Name == "Cookie Crafter [Lv. 2200]" or v.Name == "Cake Guard [Lv. 2225]" or v.Name == "Baking Staff [Lv. 2250]" or v.Name == "Head Baker [Lv. 2275]") and (v.HumanoidRootPart.Position - POSCAKE.Position).magnitude <= 350 then
					v.HumanoidRootPart.CFrame = POSCAKE
					v.HumanoidRootPart.CanCollide = false
					v.HumanoidRootPart.Size = Vector3.new(50,50,50)
					if v.Humanoid:FindFirstChild("Animator") then
						v.Humanoid.Animator:Destroy()
					end
					sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
				end
			end
		end)
	end)
end) 

if World2 then

General.newToggle("Auto Third Sea", "ออโต้โลกที่สาม", _G.Auto_Third_World, function(value)
   _G.Auto_Third_World = value
		StopTween(_G.Auto_Third_World)
end)

General.newToggle("Auto Farm Ectoplasm", "ออโต้ฟาร์มเงินส้ม", _G.Auto_Farm_Ectoplasm, function(value)
    _G.Auto_Farm_Ectoplasm = value
		StopTween(_G.Auto_Farm_Ectoplasm)
end)

General.newToggle("Auto Farm Factory", "ออโต้ฟาร์มโรงงาน", _G.AutoFactory, function(value)
    _G.AutoFactory = value
		StopTween(_G.AutoFactory)
end)

spawn(function()
		while wait() do
			pcall(function()
				if _G.AutoFactory then
					if game:GetService("Workspace").Enemies:FindFirstChild("Core") then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if v.Name == "Core" and v.Humanoid.Health > 0 then
								repeat task.wait()
									AutoHaki()
									EquipWeapon(_G.Select_Weapon)
									topos(CFrame.new(448.46756, 199.356781, -441.389252))
									game:GetService("VirtualUser"):CaptureController()
									game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
								until v.Humanoid.Health <= 0 or _G.AutoFactory == false
							end
						end
					else
						topos(CFrame.new(448.46756, 199.356781, -441.389252))
					end
				end
			end)
		end
	end)
end

if World1 then

General.newToggle("Auto Second Sea", "ออโต้โลกที่สอง", _G.Auto_New_World, function(value)
  _G.Auto_New_World = value
		StopTween(_G.Auto_New_World)
  end)
end

General.newToggle("Auto BF Mastery", "ออโต้ฟาร์มมาสผล", _G.AutoFarmFruitMastery, function(value)
    _G.AutoFarmFruitMastery = value
	StopTween(_G.AutoFarmFruitMastery)
	if _G.AutoFarmFruitMastery == false then
		UseSkill = false
	end
end)

spawn(function()
	while wait() do
		if _G.AutoFarmFruitMastery then
			pcall(function()
				local QuestTitle = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text
				if not string.find(QuestTitle, NameMon) then
					StartMagnet = false
					UseSkill = false
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
				end
				if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
					StartMasteryFruitStartMagnet = false
					UseSkill = false
					CheckQuest()
					repeat wait()
						topos(CFrameQuest)
					until (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 or not _G.AutoFarmFruitMastery
					if (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 then
						wait(1.2)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NameQuest,LevelQuest)
						wait(0.5)
					end
				elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
					CheckQuest()
					if game:GetService("Workspace").Enemies:FindFirstChild(Ms) then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
								if v.Name == Ms then
									if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
										HealthMs = v.Humanoid.MaxHealth * _G.Kill_At/100
										repeat task.wait()
											if v.Humanoid.Health <= HealthMs then
												AutoHaki()
												EquipWeapon(game:GetService("Players").LocalPlayer.Data.DevilFruit.Value)
												topos(v.HumanoidRootPart.CFrame * MethodFarm)
												v.HumanoidRootPart.CanCollide = false
												PosMonMasteryFruit = v.HumanoidRootPart.CFrame
												v.Humanoid.WalkSpeed = 0
												v.Head.CanCollide = false
												UseSkill = true
											else
												UseSkill = false
												AutoHaki()
												EquipWeapon(_G.Select_Weapon)
												topos(v.HumanoidRootPart.CFrame * MethodFarm)
												v.HumanoidRootPart.CanCollide = false
												v.HumanoidRootPart.Size = Vector3.new(50,50,50)
												PosMonMasteryFruit = v.HumanoidRootPart.CFrame
												v.Humanoid.WalkSpeed = 0
												v.Head.CanCollide = false
											end
											StartMasteryFruitStartMagnet = true
											game:GetService'VirtualUser':CaptureController()
											game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										until not _G.AutoFarmFruitMastery or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
									else
										UseSkill = false
										StartMasteryFruitStartMagnet = false
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
									end
								end
							end
						end
					else
						StartMasteryFruitStartMagnet = false
						UseSkill = false
						local Mob = game:GetService("ReplicatedStorage"):FindFirstChild(Ms)
						if Mob then
							topos(Mob.HumanoidRootPart.CFrame * MethodFarm)
						else
							if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame.Y <= 1 then
								game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = true
								task.wait()
								game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = false
							end
						end
					end
				end
			end)
		end
	end
end)

spawn(function()
	while wait() do
		if UseSkill then
			pcall(function()
				CheckQuest()
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if game:GetService("Players").LocalPlayer.Character:FindFirstChild(game:GetService("Players").LocalPlayer.Data.DevilFruit.Value) then
						MasBF = game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Data.DevilFruit.Value].Level.Value
					elseif game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(game:GetService("Players").LocalPlayer.Data.DevilFruit.Value) then
						MasBF = game:GetService("Players").LocalPlayer.Backpack[game:GetService("Players").LocalPlayer.Data.DevilFruit.Value].Level.Value
					end
					if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon-Dragon") then
						if _G.SkillZ then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
						end
						if _G.SkillX then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
						end
						if _G.SkillC then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"C",false,game)
							wait(2)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
						end
					elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Venom-Venom") then
						if _G.SkillZ then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
						end
						if _G.SkillX then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
						end
						if _G.SkillC then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"C",false,game)
							wait(2)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
						end
					elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Human-Human: Buddha") then
						if _G.SkillZ and game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Size == Vector3.new(2, 2.0199999809265, 1) then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
						end
						if _G.SkillX then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
						end
						if _G.SkillC then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"C",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
						end
						if _G.SkillV then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"V",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"V",false,game)
						end
					elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild(game:GetService("Players").LocalPlayer.Data.DevilFruit.Value) then
						if _G.SkillZ then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
						end
						if _G.SkillX then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
						end
						if _G.SkillC then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"C",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
						end
						if _G.SkillV then
							local args = {
								[1] = PosMonMasteryFruit.Position
							}
							game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
							game:GetService("VirtualInputManager"):SendKeyEvent(true,"V",false,game)
							game:GetService("VirtualInputManager"):SendKeyEvent(false,"V",false,game)
						end
					end
				end
			end)
		end
	end
end)

spawn(function()
	game:GetService("RunService").RenderStepped:Connect(function()
		pcall(function()
			if UseSkill then
				for i,v in pairs(game:GetService("Players").LocalPlayer.PlayerGui.Notifications:GetChildren()) do
					if v.Name == "NotificationTemplate" then
						if string.find(v.Text,"Skill locked!") then
							v:Destroy()
						end
					end
				end
			end
		end)
	end)
end)

spawn(function()
	pcall(function()
		game:GetService("RunService").RenderStepped:Connect(function()
			if UseSkill then
				local args = {
					[1] = PosMonMasteryFruit.Position
				}
				game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Data.DevilFruit.Value].RemoteEvent:FireServer(unpack(args))
			end
		end)
	end)
end)

General.newToggle("Auto Gun Mastery", "ออโต้ฟาร์มมาสปืน", _G.AutoFarmGunMastery, function(value)
   _G.AutoFarmGunMastery = value
	StopTween(_G.AutoFarmGunMastery)
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.AutoFarmGunMastery then
				local QuestTitle = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text
				if not string.find(QuestTitle, NameMon) then
					StartMagnet = false
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
				end
				if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
					StartMasteryGunStartMagnet = false
					CheckQuest()
					topos(CFrameQuest)
					if (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10 then
						wait(1.2)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest", NameQuest, LevelQuest)
					end
				elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
					CheckQuest()
					if game:GetService("Workspace").Enemies:FindFirstChild(Ms) then
						pcall(function()
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == Ms then
									repeat task.wait()
										if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
											HealthMs = v.Humanoid.MaxHealth * _G.Kill_At/100
											if v.Humanoid.Health <= HealthMs then
												EquipWeapon(SelectWeaponGun)
												topos(v.HumanoidRootPart.CFrame * MethodFarm)
												v.Humanoid.WalkSpeed = 0
												v.HumanoidRootPart.CanCollide = false
												v.HumanoidRootPart.Size = Vector3.new(2,2,1)
												v.Head.CanCollide = false
												local args = {
													[1] = v.HumanoidRootPart.Position,
													[2] = v.HumanoidRootPart
												}
												game:GetService("Players").LocalPlayer.Character[SelectWeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
											else
												AutoHaki()
												EquipWeapon(_G.Select_Weapon)
												v.Humanoid.WalkSpeed = 0
												v.HumanoidRootPart.CanCollide = false
												v.Head.CanCollide = false
												v.HumanoidRootPart.Size = Vector3.new(50,50,50)
												topos(v.HumanoidRootPart.CFrame * MethodFarm)
												game:GetService'VirtualUser':CaptureController()
												game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
											end
											StartMasteryGunStartMagnet = true
											PosMonMasteryGun = v.HumanoidRootPart.CFrame
										else
											StartMasteryGunStartMagnet = false
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
										end
									until v.Humanoid.Health <= 0 or _G.AutoFarmGunMastery == false or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
									StartMasteryGunStartMagnet = false
								end
							end
						end)
					else
						StartMasteryGunStartMagnet = false
						local Mob = game:GetService("ReplicatedStorage"):FindFirstChild(Ms)
						if Mob then
							topos(Mob.HumanoidRootPart.CFrame * MethodFarm)
						else
							if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame.Y <= 1 then
								game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = true
								task.wait()
								game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = false
							end
						end
					end
				end
			end
		end
	end)
end)

if World3 then

General.newToggle("Auto Electric Claw", "ออโต้ทำกรงเล็บไฟ้า", _G.Auto_Electric_Claw, function(value)
   _G.Auto_Electric_Claw = value
end)

spawn(function()
		while wait() do 
			if _G.Auto_Electric_Claw then
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") or game.Players.LocalPlayer.Character:FindFirstChild("Electro") or game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw") then
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
						_G.Select_Weapon = "Electric Claw"
					end  
					if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
						_G.Select_Weapon = "Electric Claw"
					end  
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 399 then
						_G.Select_Weapon = "Electro"
					end 
				else
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
				end
			end
		end
	end)

General.newToggle("Auto Dragon Talon", "ออโต้ทำหมัดมังกร", _G.Auto_Dragon_Talon, function(value)
    _G.Auto_Dragon_Talon = value
end)

spawn(function()
		while wait() do
			if _G.Auto_Dragon_Talon then
				if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Talon") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Talon") then
					if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
						_G.Select_Weapon = "Dragon Talon"
					end  
					if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw") and game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
						_G.Select_Weapon = "Dragon Talon"
					end  
					if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 399 then
						_G.Select_Weapon = "Dragon Claw"
					end 
				else 
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2")
				end
			end
		end
	end)

General.newToggle("Auto God Human", "ออโต้ทำก็อดฮิวแมน", _G.Auto_God_Human, function(value)
  _G.Auto_God_Human = value
  end)
end

spawn(function()
	while task.wait() do
		if _G.Auto_God_Human then
			pcall(function()
				if game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") or game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Death Step") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Death Step") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fishman Karate") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Sharkman Karate") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Sharkman Karate") or game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") or game.Players.LocalPlayer.Character:FindFirstChild("Electro") or game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Talon") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Talon") or game.Players.LocalPlayer.Character:FindFirstChild("Godhuman") or game.Players.LocalPlayer.Backpack:FindFirstChild("Godhuman") then
					if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman",true) == 1 then
						if game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman") and game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") and game.Players.LocalPlayer.Character:FindFirstChild("Superhuman").Level.Value >= 400 then
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
						end
					else
						game.StarterGui:SetCore("SendNotification", {
							Title = "Notification", 
							Text = "Not Have Superhuman" ,
							Icon = "http://www.roblox.com/asset/?id=",
							Duration = 2.5
						})
					end
					if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep",true) == 1 then
						if game.Players.LocalPlayer.Backpack:FindFirstChild("Death Step") and game.Players.LocalPlayer.Backpack:FindFirstChild("Death Step").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Death Step") and game.Players.LocalPlayer.Character:FindFirstChild("Death Step").Level.Value >= 400 then
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
						end
					else
						game.StarterGui:SetCore("SendNotification", {
							Title = "Notification", 
							Text = "Not Have Death Step" ,
							Icon = "http://www.roblox.com/asset/?id=",
							Duration = 2.5
						})
					end
					if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate",true) == 1 then
						if game.Players.LocalPlayer.Backpack:FindFirstChild("Sharkman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Sharkman Karate").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Sharkman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Sharkman Karate").Level.Value >= 400 then
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
						end
					else
						game.StarterGui:SetCore("SendNotification", {
							Title = "Notification", 
							Text = "Not Have SharkMan Karate" ,
							Icon = "http://www.roblox.com/asset/?id=",
							Duration = 2.5
						})
					end
					if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw",true) == 1 then
						if game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw").Level.Value >= 400 then
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
						end
					else
						game.StarterGui:SetCore("SendNotification", {
							Title = "Notification", 
							Text = "Not Have Electric Claw" ,
							Icon = "http://www.roblox.com/asset/?id=",
							Duration = 2.5
						})
					end
					if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon",true) == 1 then
						if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Talon") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Talon").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Dragon Talon") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Talon").Level.Value >= 400 then
							if string.find(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman",true), "Bring") then
								game.StarterGui:SetCore("SendNotification", {
									Title = "Notification", 
									Text = "Not Have Enough Material" ,
									Icon = "http://www.roblox.com/asset/?id=",
									Duration = 2.5
								})
							else
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman")
							end
						end
					else
						game.StarterGui:SetCore("SendNotification", {
							Title = "Notification", 
							Text = "Not Have Dragon Talon" ,
							Icon = "http://www.roblox.com/asset/?id=",
							Duration = 2.5
						})
					end
				else
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
				end
			end)
		end
	end
end)

General.newToggle("Auto Elite Hunter", "ออโต้ฟาร์มอิลีคฮันเตอร์", _G.Auto_Elite_Hunter, function(value)
    _G.Auto_Elite_Hunter = value
	StopTween(_G.Auto_Elite_Hunter)
end)

General.newToggle("Auto Elite Hunter Hop", "ไม่มีคำแปล", _G.Auto_Elite_Hunter_Hop, function(value)
   _G.Auto_Elite_Hunter_Hop = value
end)

spawn(function()
	while wait() do
		if _G.Auto_Elite_Hunter and World3 then
			pcall(function()
				if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
					if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,"Diablo") or string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,"Deandre") or string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,"Urban") then
						if game:GetService("Workspace").Enemies:FindFirstChild("Diablo [Lv. 1750]") or game:GetService("Workspace").Enemies:FindFirstChild("Deandre [Lv. 1750]") or game:GetService("Workspace").Enemies:FindFirstChild("Urban [Lv. 1750]") then
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == "Diablo [Lv. 1750]" or v.Name == "Deandre [Lv. 1750]" or v.Name == "Urban [Lv. 1750]" then
									if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
										repeat wait()
											AutoHaki()
											EquipWeapon(_G.Select_Weapon)
											v.HumanoidRootPart.CanCollide = false
											v.Humanoid.WalkSpeed = 0
											v.HumanoidRootPart.Size = Vector3.new(50,50,50)
											topos(v.HumanoidRootPart.CFrame * MethodFarm)
											game:GetService("VirtualUser"):CaptureController()
											game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
											sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
										until _G.Auto_Elite_Hunter == false or v.Humanoid.Health <= 0 or not v.Parent
									end
								end
							end
						else
							if game:GetService("ReplicatedStorage"):FindFirstChild("Diablo [Lv. 1750]") then
								topos(game:GetService("ReplicatedStorage"):FindFirstChild("Diablo [Lv. 1750]").HumanoidRootPart.CFrame * MethodFarm)
							elseif game:GetService("ReplicatedStorage"):FindFirstChild("Deandre [Lv. 1750]") then
								topos(game:GetService("ReplicatedStorage"):FindFirstChild("Deandre [Lv. 1750]").HumanoidRootPart.CFrame * MethodFarm)
							elseif game:GetService("ReplicatedStorage"):FindFirstChild("Urban [Lv. 1750]") then
								topos(game:GetService("ReplicatedStorage"):FindFirstChild("Urban [Lv. 1750]").HumanoidRootPart.CFrame * MethodFarm)
							end
						end                    
					end
				else
					if _G.Auto_Elite_Hunter_Hop and game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("EliteHunter") == "I don't have anything for you right now. Come back later." then
						hop()
					else
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter")
					end
				end
			end)
		end
	end
end)

General.newToggle("Auto Swan Glasses", "ออโต้แว่นโดฟา", _G.Auto_Swan_Glasses, function(value)
   	_G.Auto_Swan_Glasses = value
	StopTween(_G.Auto_Swan_Glasses)
end)

General.newToggle("Auto Swan Glasses Hop", "", _G.Auto_Swan_Glasses_Hop, function(value)
    _G.Auto_Swan_Glasses_Hop = value
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_Swan_Glasses and game.ReplicatedStorage:FindFirstChild("Don Swan [Lv. 1000] [Boss]") or game.Workspace.Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
				if game.Workspace.Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if _G.Auto_Swan_Glasses and v.Name == "Don Swan [Lv. 1000] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
							repeat wait()  
								EquipWeapon(_G.Select_Weapon)
								AutoHaki()
								topos(v.HumanoidRootPart.CFrame * MethodFarm)
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not _G.Auto_Swan_Glasses or v.Humanoid.Health <= 0 or not v.Parent
						end
					end
				else
					topos(CFrame.new(2289.47900390625, 15.152046203613281, 739.512939453125))
				end
			else
				if _G.Auto_Swan_Glasses_Hop then
					hop()
				end
			end
		end)
	end
end)

General.newToggle("Auto Bartilo Quest", "ออโต้บาร์โทรมีโอ [แปลถูกมั้ยวะ]", _G.Auto_Bartilo_Quest, function(value)
    _G.Auto_Bartilo_Quest = value
	StopTween(_G.Auto_Bartilo_Quest)
end)

General.newToggle("Auto Evo Race V2", "ออโต้อีโวเผ่าวีสอง", _G.Auto_Evo_Race_V2, function(value)
   	_G.Auto_Evo_Race_V2 = value
	StopTween(_G.Auto_Evo_Race_V2)
end)

spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function()
		pcall(function()
			for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
				if _G.Auto_Evo_Race_V2 and StartEvoStartMagnet and v.Name == "Swan Pirate [Lv. 775]" and (v.HumanoidRootPart.Position - PosMonEvo.Position).magnitude <= 350 then
					v.HumanoidRootPart.CFrame = PosMonEvo
					v.HumanoidRootPart.CanCollide = false
					v.HumanoidRootPart.Size = Vector3.new(50,50,50)
					if v.Humanoid:FindFirstChild("Animator") then
						v.Humanoid.Animator:Destroy()
					end
					sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
				end
			end
		end)
	end)
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.Auto_Evo_Race_V2 then
				if not game:GetService("Players").LocalPlayer.Data.Race:FindFirstChild("Evolved") then
					if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 0 then
						topos(CFrame.new(-2779.83521, 72.9661407, -3574.02002, -0.730484903, 6.39014104e-08, -0.68292886, 3.59963224e-08, 1, 5.50667032e-08, 0.68292886, 1.56424669e-08, -0.730484903))
						if (Vector3.new(-2779.83521, 72.9661407, -3574.02002) - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 4 then
							wait(1.3)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","2")
						end
					elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 1 then
						pcall(function()
							if not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 1") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 1") then
								topos(game:GetService("Workspace").Flower1.CFrame)
							elseif not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 2") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 2") then
								topos(game:GetService("Workspace").Flower2.CFrame)
							elseif not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 3") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 3") then
								if game:GetService("Workspace").Enemies:FindFirstChild("Swan Pirate [Lv. 775]") then
									for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
										if v.Name == "Swan Pirate [Lv. 775]" then
											repeat wait()
												AutoHaki()
												EquipWeapon(_G.Select_Weapon)
												topos(v.HumanoidRootPart.CFrame * MethodFarm)
												v.HumanoidRootPart.CanCollide = false
												v.HumanoidRootPart.Size = Vector3.new(50,50,50)
												game:GetService'VirtualUser':CaptureController()
												game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
												PosMonEvo = v.HumanoidRootPart.CFrame
												StartEvoStartMagnet = true
											until game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 3") or not v.Parent or v.Humanoid.Health <= 0 or _G.Auto_Evo_Race_V2 == false
											StartEvoStartMagnet = false
										end
									end
								else
									StartEvoStartMagnet = false
									topos(CFrame.new(980.0985107421875, 121.331298828125, 1287.2093505859375))
								end
							end
						end)
					elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 2 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","3")
					end
				end
			end
		end
	end)
end)


General.newToggle("Auto Serpent Bow", "", _G.Auto_Serpent_Bow, function(value)
   _G.Auto_Serpent_Bow = value
	StopTween(_G.Auto_Serpent_Bow)
end)

General.newToggle("Auto Serpent Bow Hop", ", _G.Auto_Serpent_Bow_Hop, function(value)
    _G.Auto_Serpent_Bow_Hop = value
	StopTween(_G.Auto_Serpent_Bow_Hop)
end)

spawn(function()
	while wait() do
		if _G.Auto_Serpent_Bow then
			pcall(function()
				if _G.Auto_Serpent_Bow and game.ReplicatedStorage:FindFirstChild("Island Empress [Lv. 1675] [Boss]") or game.Workspace.Enemies:FindFirstChild("Island Empress [Lv. 1675] [Boss]") then
					if game.Workspace.Enemies:FindFirstChild("Island Empress [Lv. 1675] [Boss]") then
						for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
							if v.Name == "Island Empress [Lv. 1675] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
								repeat wait()
									AutoHaki()
									EquipWeapon(_G.Select_Weapon)
									topos(v.HumanoidRootPart.CFrame * MethodFarm)
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								until _G.Auto_Serpent_Bow or v.Humanoid.Health <= 0 or not v.Parent
							end
						end
					else
						topos(CFrame.new(5764.1826171875, 700.425537109375, 141.11996459960938))
					end
				else
					if _G.Auto_Serpent_Bow_Hop then
						hop()
					end
				end
			end)
		end
	end
end)

General.newToggle("Auto Mirage Island", "", _G.Mirage, function(value)
  _G.Mirage = value
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.Mirage then
				if game:GetService("Workspace").Map:FindFirstChild("MysticIsland") then
					function toTargetWait(a)local b=(a.p-game.Players.LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).Magnitude;tweenrach=game:GetService('TweenService'):Create(game.Players.LocalPlayer.Character:WaitForChild("HumanoidRootPart"),TweenInfo.new(b/250,Enum.EasingStyle.Linear),{CFrame=a})tweenrach:Play()end;toTargetWait(workspace.Map.MysticIsland.PrimaryPart.CFrame*CFrame.new(0,250,0))
				else
					game.StarterGui:SetCore("SendNotification", {
						Title = ""; -- the title (ofc)
						Text = "Mirage not Found!"; -- what the text says (ofc)
						Icon = "rbxassetid://"; -- the image if u want. 
						Duration = 3; -- how long the notification should in secounds
					})
					if _G.MirageHop then
						wait(6)
						Hop()
					end          
				end
			end
		end
	end)
end)

General.newToggle("Auto Mirage Island Hop", "", _G.Mystichop, function(value)
    _G.Mystichop = value
end)

General.newButton("Teleport To Timple Of Time", "", function()
    Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28286.35546875, 14895.3017578125, 102.62469482421875)
end)

General.newButton("Teleport To Lever Pull", "", function()
    topos(CFrame.new(28575.181640625, 14936.6279296875, 72.31636810302734))
end)

General.newButton("Teleport To Acient One (Must Be in Temple Of Time!)", "", function()
    topos(CFrame.new(28981.552734375, 14888.4267578125, -120.245849609375))
end)

General.newButton("Teleport To เกียร์", "", function()
   TP(game:GetService("Workspace").Map.MysticIsland:FindFirstChildOfClass("MeshPart").CFrame)
end)

General.newToggle("White Screen", "จอขาว", _G.WhiteScreen, function(value)
   
   _G.WhiteScreen = value

	if _G.WhiteScreen == true then
		game:GetService("RunService"):Set3dRenderingEnabled(false)
	elseif _G.WhiteScreen == false then
		game:GetService("RunService"):Set3dRenderingEnabled(true)
	end
end)

General.newToggle("Bring Mob", "รวมมอน", _G.BringExtra, function(value)
   _G.BringExtra = value
end)

spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function() CheckQuest()
		pcall(function()
			if _G.BringExtra then
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if _G.Auto_Farm_Level and StartMagnet and v.Name ~= "Ice Admiral [Lv. 700] [Boss]" and v.Name ~= "Don Swan [Lv. 3000] [Boss]" and v.Name ~= "Saber Expert [Lv. 200] [Boss]" and v.Name ~= "Longma [Lv. 2000] [Boss]" and (v.HumanoidRootPart.Position - PosMon.Position).magnitude <= 350 then
						v.HumanoidRootPart.CFrame = PosMon
						v.HumanoidRootPart.CanCollide = false
						v.HumanoidRootPart.Size = Vector3.new(60,60,60)
						if v.Humanoid:FindFirstChild("Animator") then
							v.Humanoid.Animator:Destroy()
						end
						sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
					end
				end
			end
		end)
	end)
end)

General.newToggle("Bring Mob Normal", "รวมมอนธรรมดา", _G.BringNormal, function(value)
    _G.BringNormal = value
end)

spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function() CheckQuest()
		pcall(function()
			if _G.BringNormal then
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if _G.Auto_Farm_Level and StartMagnet and v.Name == Ms and (v.HumanoidRootPart.Position - PosMon.Position).magnitude <= 350 then
						v.HumanoidRootPart.CFrame = PosMon
						v.HumanoidRootPart.CanCollide = false
						v.HumanoidRootPart.Size = Vector3.new(50,50,50)
						if v.Humanoid:FindFirstChild("Animator") then
							v.Humanoid.Animator:Destroy()
						end
						sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
					end
				end
			end
		end)
	end)
end)

General.newToggle("Anti AFK", "มันใช้บ่ได้เด้อใช้มาเสยๆ", _G.AFK, function(value)
   _G.AFK = value
end)

General.newToggle("Super Fast Attack", "ชุปเปอร์โจมตีเร็ว", true, function(value)
  
end)

General.newToggle("Fast Attack", "โจมตีเร็ว", _G.FastAttack, function(value)
    _G.FastAttack = value

	local SeraphFrame = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts:WaitForChild("CombatFramework")))[2]
	local VirtualUser = game:GetService('VirtualUser')
	local RigControllerR = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.RigController))[2]
	local Client = game:GetService("Players").LocalPlayer
	local DMG = require(Client.PlayerScripts.CombatFramework.Particle.Damage)

	function SeraphFuckWeapon() 
		local p13 = SeraphFrame.activeController
		local wea = p13.blades[1]
		if not wea then return end
		while wea.Parent~=game.Players.LocalPlayer.Character do wea=wea.Parent end
		return wea
	end

	function getHits(Size)
		local Hits = {}
		local Enemies = workspace.Enemies:GetChildren()
		local Characters = workspace.Characters:GetChildren()
		for i=1,#Enemies do local v = Enemies[i]
			local Human = v:FindFirstChildOfClass("Humanoid")
			if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+5 then
				table.insert(Hits,Human.RootPart)
			end
		end
		for i=1,#Characters do local v = Characters[i]
			if v ~= game.Players.LocalPlayer.Character then
				local Human = v:FindFirstChildOfClass("Humanoid")
				if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+5 then
					table.insert(Hits,Human.RootPart)
				end
			end
		end
		return Hits
	end

	task.spawn(
		function()
			while wait(0) do
				if  _G.FastAttack then
					if SeraphFrame.activeController then
						-- if v.Humanoid.Health > 0 then
						SeraphFrame.activeController.timeToNextAttack = 0
						SeraphFrame.activeController.focusStart = 0
						SeraphFrame.activeController.hitboxMagnitude = 40
						SeraphFrame.activeController.humanoid.AutoRotate = true
						SeraphFrame.activeController.increment = 1 + 1 / 1
						-- end
					end
				end
			end
		end)

	function Boost()
		spawn(function()
			game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(SeraphFuckWeapon()))
		end)
	end

	function Unboost()
		spawn(function()
			game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring(SeraphFuckWeapon()))
		end)
	end

	local cdnormal = 0
	local Animation = Instance.new("Animation")
	local CooldownFastAttack = 0
	Attack = function()
		local ac = SeraphFrame.activeController
		if ac and ac.equipped then
			task.spawn(
				function()
					if tick() - cdnormal > 0.5 then
						ac:attack()
						cdnormal = tick()
					else
						Animation.AnimationId = ac.anims.basic[2]
						ac.humanoid:LoadAnimation(Animation):Play(2, 2) --ท่าไม่ทำงานแก้เป็น (1,1)
						game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", getHits(120), 2, "")
					end
				end)
		end
	end

	b = tick()
	spawn(function()
		while wait(0) do
			if  _G.FastAttack then
				if b - tick() > 0.75 then
					wait(.2)
					b = tick()
				end
				pcall(function()
					for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
						if v.Humanoid.Health > 0 then
							if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
								Attack()
								wait(0)
								Boost()
							end
						end
					end
				end)
			end
		end
	end)

	k = tick()
	spawn(function()
		while wait(0) do
			if  _G.FastAttack then
				if k - tick() > 0.75 then
					wait(0)
					k = tick()
				end
				pcall(function()
					for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
						if v.Humanoid.Health > 0 then
							if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
								wait(0)
								Unboost()
							end
						end
					end
				end)
			end
		end
	end)
	
	tjw1 = true
	task.spawn(
		function()
			local a = game.Players.LocalPlayer
			local b = require(a.PlayerScripts.CombatFramework.Particle)
			local c = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
			if not shared.orl then
				shared.orl = c.wrapAttackAnimationAsync
			end
			if not shared.cpc then
				shared.cpc = b.play
			end
			if tjw1 then
				pcall(
					function()
						c.wrapAttackAnimationAsync = function(d, e, f, g, h)
							local i = c.getBladeHits(e, f, g)
							if i then
								b.play = function()
								end
								d:Play(15.25, 15.25, 15.25)
								h(i)
								b.play = shared.cpc
								wait(0)
								d:Stop()
							end
						end
					end
				)
			end
		end
	)



	local CameRa = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.CameraShaker)
	CameRa.CameraShakeInstance.CameraShakeState = {FadingIn = 3,FadingOut = 2,Sustained = 0,Inactive =1}

	local Client = game.Players.LocalPlayer
	local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
	local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
	task.spawn(function()
		pcall(function()
			if not shared.orl then
				shared.orl = STOPRL.wrapAttackAnimationAsync
			end
			if not shared.cpc then
				shared.cpc = STOP.play 
			end
			spawn(function()
				require(game.ReplicatedStorage.Util.CameraShaker):Stop()
				game:GetService("RunService").Stepped:Connect(function()
					STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
						local Hits = STOPRL.getBladeHits(b,c,d)
						if Hits then
							if  _G.FastAttack then
								STOP.play = function() end
								a:Play(10.1,9.1,8.1)
								func(Hits)
								STOP.play = shared.cpc
								wait(a.length * 10.5)
								a:Stop()
							else
								func(Hits)
								STOP.play = shared.cpc
								wait(a.length * 10.5)
								a:Stop()
							end
						end
					end
				end)
			end)
		end)
	end)
end)

General.newToggle("Invisble Mob", "", _G.inv, function(value)
   _G.inv = value
	while _G.inv do wait()
		pcall(function()
			for i,v in pairs(game:GetService("Workspace").Enemies:GetDescendants()) do
				if v.ClassName == "MeshPart" then
					v.Transparency = 1
				end
			end
			for i,v in pairs(game:GetService("Workspace").Enemies:GetDescendants()) do
				if v.Name == "Head" then
					v.Transparency = 1
				end
			end
			for i,v in pairs(game:GetService("Workspace").Enemies:GetDescendants()) do
				if v.ClassName == "Accessory" then
					v.Handle.Transparency = 1
				end
			end
			for i,v in pairs(game:GetService("Workspace").Enemies:GetDescendants()) do
				if v.ClassName == "Decal" then
					v.Transparency = 1
				end
			end
		end)
	end
end)

General.newToggle("Auto Law", "ออโต้ตีลอ", _G.Auto_Kill_Law, function(value)
    _G.Auto_Kill_Law = value
		StopTween(_G.Auto_Kill_Law)
end)

General.newToggle("Auto Lawd Hop", "ออโต้ตีลอแบบย้ายเซิฟ [มั้ง]", _G.Auto_Kill_LawHop, function(value)
   _G.Auto_Kill_LawHop = value
end)

spawn(function()
		while wait() do
			if _G.Auto_Kill_Law then
				pcall(function()
					if not game:GetService("Workspace").Enemies:FindFirstChild("Order [Lv. 1250] [Raid Boss]") and not game:GetService("ReplicatedStorage"):FindFirstChild("Order [Lv. 1250] [Raid Boss]") then
						if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Microchip") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Microchip") then
							fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon.Button.Main.ClickDetector)
						else
							if _G.AutoBuyBossLawChip then
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Microchip","1")
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Microchip","2")
							end
						end
					else
						if game:GetService("ReplicatedStorage"):FindFirstChild("Order [Lv. 1250] [Raid Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Order [Lv. 1250] [Raid Boss]") then
							if game:GetService("Workspace").Enemies:FindFirstChild("Order [Lv. 1250] [Raid Boss]") then
								for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
									if v.Name == "Order [Lv. 1250] [Raid Boss]" then
										repeat task.wait()
											EquipWeapon(_G.SelectWeapon)
											AutoHaki()
											topos(v.HumanoidRootPart.CFrame * CFrame.new(0,35,0))
											v.HumanoidRootPart.CanCollide = false
											game:GetService'VirtualUser':CaptureController()
											game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										until v.Humanoid.Health <= 0 or not _G.AutoBossLaw or not v.Parent
									end
								end
							else 
								if game:GetService("ReplicatedStorage"):FindFirstChild("Order [Lv. 1250] [Raid Boss]") then
									topos(game:GetService("ReplicatedStorage"):FindFirstChild("Order [Lv. 1250] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(0,35,0))
								end
							end
						end
					end
				end)
			end
		end
	end)
	
General.newButton("Buy Microchip Law", "ซื้อไมโครชิฟลอ", function()
    local args = {
			[1] = "BlackbeardReward",
			[2] = "Microchip",
			[3] = "2"
		}
		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

General.newButton("Start Raid Law", "เริ่มดันลอ", function()
    fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon.Button.Main.ClickDetector)
	end)
end


General.newToggle("Auto Farm Observation", "ไม่รู้ลืม", _G.AutoObservation, function(value)
   _G.AutoObservation = value
	StopTween(_G.AutoObservation)
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.AutoObservation then
				repeat task.wait()
					if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
						game:GetService('VirtualUser'):CaptureController()
						game:GetService('VirtualUser'):SetKeyDown('0x65')
						wait(2)
						game:GetService('VirtualUser'):SetKeyUp('0x65')
					end
				until game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") or not _G.AutoObservation
			end
		end)
	end
end)

General.newToggle("Auto Farm Observation Hop", "ลืม", _G.AutoObservation_Hop, function(value)
    _G.AutoObservation_Hop = value
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.AutoObservation then
				if game:GetService("Players").LocalPlayer.VisionRadius.Value >= 3000 then
					local NotificationHolder = loadstring(game:HttpGet("https://raw.githubusercontent.com/BocusLuke/UI/main/STX/Module.Lua"))()
					local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/BocusLuke/UI/main/STX/Client.Lua"))()
					wait(1)
					Notification:Notify(
						{Title = "", Description = "You Have Max Observation"},
						{OutlineColor = Color3.fromRGB(80, 80, 80),Time = 5, Type = "option"},
						{Image = "http://www.roblox.com/asset/?id=", ImageColor = Color3.fromRGB(255, 84, 84), Callback = function(State) print(tostring(State)) end}
					)
				else
					if World2 then
						if game:GetService("Workspace").Enemies:FindFirstChild("Water Fighter [Lv. 1450]") then
							if game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
								repeat task.wait()
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Water Fighter [Lv. 1450]").HumanoidRootPart.CFrame * CFrame.new(3,0,0)
								until _G.AutoObservation == false or not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
							else
								repeat task.wait()
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Water Fighter [Lv. 1450]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)+
										wait(1)
									if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and _G.AutoObservation_Hop == true then
										game:GetService("TeleportService"):Teleport(game.PlaceId, game:GetService("Players").LocalPlayer)
									end
								until _G.AutoObservation == false or game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
							end
						else
							TP(CFrame.new(-3184.662353515625, 58.35300064086914, -9662.85546875))
						end
					elseif World1 then
						if game:GetService("Workspace").Enemies:FindFirstChild("Galley Captain [Lv. 650]") then
							if game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
								repeat task.wait()
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Galley Captain [Lv. 650]").HumanoidRootPart.CFrame * CFrame.new(3,0,0)
								until _G.AutoObservation == false or not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
							else
								repeat task.wait()
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Galley Captain [Lv. 650]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)
									wait(1)
									if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and _G.AutoObservation_Hop == true then
										game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
									end
								until _G.AutoObservation == false or game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
							end
						else
							TP(CFrame.new(5533.29785, 88.1079102, 4852.3916))
						end
					elseif World3 then
						if game:GetService("Workspace").Enemies:FindFirstChild("Giant Islander [Lv. 1650]") then
							if game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
								repeat task.wait()
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Giant Islander [Lv. 1650]").HumanoidRootPart.CFrame * CFrame.new(3,0,0)
								until _G.AutoObservation == false or not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
							else
								repeat task.wait()
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Giant Islander [Lv. 1650]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)
									wait(1)
									if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and _G.AutoObservation_Hop == true then
										game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
									end
								until _G.AutoObservation == false or game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
							end
						else
							TP(CFrame.new(4530.3540039063, 656.75695800781, -131.60952758789))
						end
					end
				end
			end
		end
	end)
end)

Stats.newToggle("Auto Melee", "อัพหมัด", _G.Auto_Melee, function(value)
   _G.Auto_Melee = value
end)

Stats.newToggle("Auto Defense", "อัพเลือด", _G.Auto_Defense, function(value)
   _G.Auto_Defense = value
end)

Stats.newToggle("Auto Sword", "อัพดาบ", _G.Auto_Sword, function(value)
    _G.Auto_Sword = value
end)

Stats.newToggle("Auto Gun", "อัพปืน", _G.Auto_Gun, function(value)
    _G.Auto_Gun = value
end)

Stats.newToggle("Auto Devil Fruit", "อัพผล", _G.Auto_DevilFruit, function(value)
  _G.Auto_DevilFruit = value
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_Melee then
				if game:GetService("Players")["LocalPlayer"].Data.Points.Value ~= 0 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",_G.PointStats)
				end
			end
		end)
	end
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_Defense then
				if game:GetService("Players")["LocalPlayer"].Data.Points.Value ~= 0 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense",_G.PointStats)
				end
			end
		end)
	end
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_Sword then
				if game:GetService("Players")["LocalPlayer"].Data.Points.Value ~= 0 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Sword",_G.PointStats)
				end
			end
		end)
	end
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_Gun then
				if game:GetService("Players")["LocalPlayer"].Data.Points.Value ~= 0 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Gun",_G.PointStats)
				end
			end
		end)
	end
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_DevilFruit then
				if game:GetService("Players")["LocalPlayer"].Data.Points.Value ~= 0 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Demon Fruit",_G.PointStats)
				end
			end
		end)
	end
end)

General.newToggle("Auto Buy Legendary Sword", "ออโต้ซื้อสามดาบโซโล", _G.AutoBuyLegendarySword, function(value)
    _G.AutoBuyLegendarySword = Value
end)

spawn(function()
	while wait() do
		if _G.AutoBuyLegendarySword then
			pcall(function()
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("LegendarySwordDealer","1")
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("LegendarySwordDealer","2")
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("LegendarySwordDealer","3")
				if _G.AutoBuyLegendarySword_Hop and _G.AutoBuyLegendarySword and World2 then
					wait(10)
					Hop()
				end
			end)
		end 
	end
end)

General.newToggle("Auto Saber", "ออโต้ดาบแชงค์", _G.AutoSaber, function(value)
   _G.AutoSaber = value
end)

General.newToggle("Auto Saber Hop", "ออโต้ดาบแชงค์แบบย้ายเซิฟ", _G.AutoSaberHop, function(value)
   _G.AutoSaberHop = value
end)

spawn(function()
	while wait() do
		if _G.AutoSaber then
			if game.Players.localPlayer.Data.Level.Value < 200 then
			else
				if game.Workspace.Map.Jungle.Final.Part.CanCollide == false then
					if _G.AutoSaber and game.ReplicatedStorage:FindFirstChild("Saber Expert [Lv. 200] [Boss]") or game.Workspace.Enemies:FindFirstChild("Saber Expert [Lv. 200] [Boss]") then
						if game.Workspace.Enemies:FindFirstChild("Saber Expert [Lv. 200] [Boss]") then
							for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
								if v.Name == "Saber Expert [Lv. 200] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
									repeat wait()
										if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 300 then
											Farmtween = topos(v.HumanoidRootPart.Position,v.HumanoidRootPart.CFrame)
										elseif (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
											if Farmtween then
												Farmtween:Stop()
											end
											AutoHaki()
											EquipWeapon(_G.SelectWeapon)
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 30, 0)
											game:GetService'VirtualUser':CaptureController()
											game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										end
									until not _G.Auto_Saber or not v.Parent or v.Humanoid.Health <= 0
								end
							end
						else
							Questtween = topos(CFrame.new(-1405.41956, 29.8519993, 5.62435055).Position,CFrame.new(-1405.41956, 29.8519993, 5.62435055))
							if (CFrame.new(-1405.41956, 29.8519993, 5.62435055).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
								if Questtween then
									Questtween:Stop()
								end
								game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1405.41956, 29.8519993, 5.62435055, 0.885240912, 3.52892613e-08, 0.465132833, -6.60881128e-09, 1, -6.32913171e-08, -0.465132833, 5.29540891e-08, 0.885240912)
							end
						end
					else
						if _G.AutoSaberHop then
							Hop()
						end
					end
				elseif game.Players.LocalPlayer.Backpack:FindFirstChild("Relic") or game.Players.LocalPlayer.Character:FindFirstChild("Relic") and game.Players.localPlayer.Data.Level.Value >= 200 then
					EquipWeapon("Relic")
					wait(0.5)
					Questtween = topos(CFrame.new(-1405.41956, 29.8519993, 5.62435055).Position,CFrame.new(-1405.41956, 29.8519993, 5.62435055))
					if (CFrame.new(-1405.41956, 29.8519993, 5.62435055).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
						if Questtween then
							Questtween:Stop()
						end
						game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1405.41956, 29.8519993, 5.62435055, 0.885240912, 3.52892613e-08, 0.465132833, -6.60881128e-09, 1, -6.32913171e-08, -0.465132833, 5.29540891e-08, 0.885240912)
					end
				else
					if Workspace.Map.Jungle.QuestPlates.Door.CanCollide == false then
						if game.Workspace.Map.Desert.Burn.Part.CanCollide == false then
							if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","SickMan") == 0 then
								if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon") == 0 then
									if game.Workspace.Enemies:FindFirstChild("Mob Leader [Lv. 120] [Boss]") then
										for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
											if _G.AutoSaber and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == "Mob Leader [Lv. 120] [Boss]" then
												repeat
													pcall(function() wait() 
														if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 300 then
															Farmtween = topos(v.HumanoidRootPart.Position,v.HumanoidRootPart.CFrame)
														elseif (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
															if Farmtween then
																Farmtween:Stop()
															end
															AutoHaki()
															EquipWeapon(_G.SelectWeapon)
															if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
																local args = {
																	[1] = "Buso"
																}
																game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
															end
															game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 30, 0)
															game:GetService'VirtualUser':CaptureController()
															game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
														end
													end)
												until not _G.AutoSaber or not v.Parent or v.Humanoid.Health <= 0
											end
										end
									else
										Questtween = topos(CFrame.new(-2848.59399, 7.4272871, 5342.44043).Position,CFrame.new(-2848.59399, 7.4272871, 5342.44043))
										if (CFrame.new(-2848.59399, 7.4272871, 5342.44043).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
											if Questtween then
												Questtween:Stop()
											end
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2848.59399, 7.4272871, 5342.44043, -0.928248107, -8.7248246e-08, 0.371961564, -7.61816636e-08, 1, 4.44474857e-08, -0.371961564, 1.29216433e-08, -0.928248107)
										end
									end
									elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon") == 1 then
									if game.Players.LocalPlayer.Backpack:FindFirstChild("Relic") or game.Players.LocalPlayer.Character:FindFirstChild("Relic") then
										EquipWeapon("Relic")
										wait(0.5)
										Questtween = topos(CFrame.new(-1405.41956, 29.8519993, 5.62435055).Position,CFrame.new(-1405.41956, 29.8519993, 5.62435055))
										if (CFrame.new(-1405.41956, 29.8519993, 5.62435055).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
											if Questtween then
												Questtween:Stop()
											end
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1405.41956, 29.8519993, 5.62435055)
										end
									else
										Questtween = topos(CFrame.new(-910.979736, 13.7520342, 4078.14624).Position,CFrame.new(-910.979736, 13.7520342, 4078.14624))
										if (CFrame.new(-910.979736, 13.7520342, 4078.14624).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
											if Questtween then
												Questtween:Stop()
											end
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-910.979736, 13.7520342, 4078.14624, 0.00685182028, -1.53155766e-09, -0.999976516, 9.15205245e-09, 1, -1.46888401e-09, 0.999976516, -9.14177267e-09, 0.00685182028)
											wait(.5)
											local args = {
												[1] = "ProQuestProgress",
												[2] = "RichSon"
											}
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
										end
									end
								else
									Questtween = topos(CFrame.new(-910.979736, 13.7520342, 4078.14624).Position,CFrame.new(-910.979736, 13.7520342, 4078.14624))
									if (CFrame.new(-910.979736, 13.7520342, 4078.14624).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
										if Questtween then
											Questtween:Stop()
										end
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-910.979736, 13.7520342, 4078.14624)
										local args = {
											[1] = "ProQuestProgress",
											[2] = "RichSon"
										}
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
									end
								end
							else
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Cup") or game.Players.LocalPlayer.Character:FindFirstChild("Cup") then
									EquipWeapon("Cup")
									if game.Players.LocalPlayer.Character.Cup.Handle:FindFirstChild("TouchInterest") then
										Questtween = topos(CFrame.new(1397.229, 37.3480148, -1320.85217).Position,CFrame.new(1397.229, 37.3480148, -1320.85217))
										if (CFrame.new(1397.229, 37.3480148, -1320.85217).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
											if Questtween then
												Questtween:Stop()
											end
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1397.229, 37.3480148, -1320.85217, -0.11285457, 2.01368788e-08, 0.993611455, 1.91641178e-07, 1, 1.50028845e-09, -0.993611455, 1.90586206e-07, -0.11285457)
										end
									else
										wait(0.5)
										if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","SickMan") ~= 0 then
											local args = {
												[1] = "ProQuestProgress",
												[2] = "SickMan"
											}
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
										end
									end
								else
									Questtween = topos(game.Workspace.Map.Desert.Cup.Position,game.Workspace.Map.Desert.Cup.CFrame)
									if (game.Workspace.Map.Desert.Cup.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
										if Questtween then
											Questtween:Stop()
										end
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Map.Desert.Cup.CFrame
									end
									firetouchinterest(game.Workspace.Map.Desert.Cup.TouchInterest,game.Players.LocalPlayer.Character.Head, 1)
								end
							end
						else
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Torch") or game.Players.LocalPlayer.Character:FindFirstChild("Torch") then
								EquipWeapon("Torch")
								Questtween = topos(CFrame.new(1114.87708, 4.9214654, 4349.8501).Position,CFrame.new(1114.87708, 4.9214654, 4349.8501))
								if (CFrame.new(1114.87708, 4.9214654, 4349.8501).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
									if Questtween then
										Questtween:Stop()
									end
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1114.87708, 4.9214654, 4349.8501, -0.612586915, -9.68697833e-08, 0.790403247, -1.2634203e-07, 1, 2.4638446e-08, -0.790403247, -8.47679615e-08, -0.612586915)
								end
							else
								Questtween = topos(CFrame.new(-1610.00757, 11.5049858, 164.001587).Position,CFrame.new(-1610.00757, 11.5049858, 164.001587))
								if (CFrame.new(-1610.00757, 11.5049858, 164.001587).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
									if Questtween then
										Questtween:Stop()
									end
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1610.00757, 11.5049858, 164.001587, 0.984807551, -0.167722285, -0.0449818149, 0.17364943, 0.951244235, 0.254912198, 3.42372805e-05, -0.258850515, 0.965917408)
								end
							end
						end
					else
						for i,v in pairs(Workspace.Map.Jungle.QuestPlates:GetChildren()) do
							if v:IsA("Model") then wait()
								if v.Button.BrickColor ~= BrickColor.new("Camo") then
									repeat wait()
										Questtween = topos(v.Button.Position,v.Button.CFrame)
										if (v.Button.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
											if Questtween then
												Questtween:Stop()
											end
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Button.CFrame
										end
									until not _G.AutoSaber or v.Button.BrickColor == BrickColor.new("Camo")
								end
							end
						end    
					end
				end
			end 
		end
	end
end)

General.newToggle("Auto Tushita Sword", "ตอนนี้ 22:52 ละนะ", _G.Autotushita, function(value)
    _G.Autotushita = value
end)

spawn(function()
	while wait() do
		if _G.Autotushita then
			if game:GetService("Workspace").Enemies:FindFirstChild("Longma [Lv. 2000] [Boss]") then
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if v.Name == ("Longma [Lv. 2000] [Boss]" or v.Name == "Longma [Lv. 2000] [Boss]") and v.Humanoid.Health > 0 and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") then
						repeat wait()
							StartMagnet = true
							AutoHaki()
							if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Select_Weapon) then
								wait()
								EquipWeapon(_G.Select_Weapon)
							end
							PosMon = v.HumanoidRootPart.CFrame
							game:GetService'VirtualUser':CaptureController()
							game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							v.HumanoidRootPart.Size = Vector3.new(60,60,60)
							v.Humanoid.JumpPower = 0
							v.Humanoid.WalkSpeed = 0
							v.HumanoidRootPart.CanCollide = false
							v.Humanoid:ChangeState(11)
							topos(v.HumanoidRootPart.CFrame * MethodFarm)
						until not _G.Autotushita or not v.Parent or v.Humanoid.Health <= 0
						StartMagnet = false
					end
				end
			else
				topos(CFrame.new(-10238.875976563, 389.7912902832, -9549.7939453125))
			end
		end
	end
end)

General.newToggle("Auto Dragon Trident", "ถ้าไม่มีคนใช้นิกูท้อเลย", _G.Auto_Dragon_Trident, function(value)
    _G.Auto_Dragon_Trident = value
	StopTween(_G.Auto_Dragon_Trident)
end)

General.newToggle("Auto Dragon Trident Hop", "ไม่รู้ลืม", _G.Auto_Dragon_Trident_Hop, function(value)
  _G.Auto_Dragon_Trident_Hop = value
end)

spawn(function()
	while wait() do
		if _G.Auto_Dragon_Trident then
			pcall(function()
				if _G.Auto_Dragon_Trident and game.ReplicatedStorage:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") or game.Workspace.Enemies:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
					if game.Workspace.Enemies:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
						for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
							if v.Name == "Tide Keeper [Lv. 1475] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
								repeat wait()
									EquipWeapon(_G.Select_Weapon)
									AutoHaki()
									topos(v.HumanoidRootPart.CFrame * MethodFarm)
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								until _G.Auto_Dragon_Trident or v.Humanoid.Health <= 0 or not v.Parent
							end
						end
					else
						topos(CFrame.new(-3914.830322265625, 123.29389190673828, -11516.8642578125))
					end
				else
					if _G.Auto_Dragon_Trident_Hop then
						hop()
					end
				end
			end)
		end
	end
end)

General.newToggle("Auto Soul Guitar", "ออโต้ทำกีต้าบลู๊ค [มั้ง]", _G.AutoNevaSoulGuitar, function(value)
    _G.AutoNevaSoulGuitar = value    
	StopTween(_G.AutoNevaSoulGuitar)
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.AutoNevaSoulGuitar then
				if GetWeaponInventory("Soul Guitar") == false then
					if (CFrame.new(-9681.458984375, 6.139880657196045, 6341.3720703125).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 5000 then
						if game:GetService("Workspace").NPCs:FindFirstChild("Skeleton Machine") then
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("soulGuitarBuy",true)
						else
							if game:GetService("Workspace").Map["Haunted Castle"].Candle1.Transparency == 0 then
								if game:GetService("Workspace").Map["Haunted Castle"].Placard1.Left.Part.Transparency == 0 then
									Quest2 = true
									repeat wait() topos(CFrame.new(-8762.69140625, 176.84783935546875, 6171.3076171875)) until (CFrame.new(-8762.69140625, 176.84783935546875, 6171.3076171875).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 or not _G.AutoNevaSoulGuitar
									wait(1)
									fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"].Placard7.Left.ClickDetector)
									wait(1)
									fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"].Placard6.Left.ClickDetector)
									wait(1)
									fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"].Placard5.Left.ClickDetector)
									wait(1)
									fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"].Placard4.Right.ClickDetector)
									wait(1)
									fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"].Placard3.Left.ClickDetector)
									wait(1)
									fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"].Placard2.Right.ClickDetector)
									wait(1)
									fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"].Placard1.Right.ClickDetector)
									wait(1)
								elseif game:GetService("Workspace").Map["Haunted Castle"].Tablet.Segment1:FindFirstChild("ClickDetector") then
									if game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part1:FindFirstChild("ClickDetector") then
										Quest4 = true
										repeat wait() topos(CFrame.new(-9553.5986328125, 65.62338256835938, 6041.58837890625)) until (CFrame.new(-9553.5986328125, 65.62338256835938, 6041.58837890625).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 or not _G.AutoNevaSoulGuitar
										wait(1)
										topos(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part3.CFrame)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part3.ClickDetector)
										wait(1)
										topos(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part4.CFrame)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part4.ClickDetector)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part4.ClickDetector)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part4.ClickDetector)
										wait(1)
										topos(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part6.CFrame)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part6.ClickDetector)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part6.ClickDetector)
										wait(1)
										topos(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part8.CFrame)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part8.ClickDetector)
										wait(1)
										topos(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part10.CFrame)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part10.ClickDetector)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part10.ClickDetector)
										wait(1)
										fireclickdetector(game:GetService("Workspace").Map["Haunted Castle"]["Lab Puzzle"].ColorFloor.Model.Part10.ClickDetector)
									else
										Quest3 = true
										--Not Work Yet
									end
								else
									if game:GetService("Workspace").NPCs:FindFirstChild("Ghost") then
										local args = {
											[1] = "GuitarPuzzleProgress",
											[2] = "Ghost"
										}

										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
									end
									if game.Workspace.Enemies:FindFirstChild("Living Zombie [Lv. 2000]") then
										for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
											if v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
												if v.Name == "Living Zombie [Lv. 2000]" then
													EquipWeapon(_G.Select_Weapon)
													v.HumanoidRootPart.Size = Vector3.new(60,60,60)
													v.HumanoidRootPart.Transparency = 1
													v.Humanoid.JumpPower = 0
													v.Humanoid.WalkSpeed = 0
													v.HumanoidRootPart.CanCollide = false
													v.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,20,0)
													topos(CFrame.new(-10160.787109375, 138.6616973876953, 5955.03076171875))
													game:GetService'VirtualUser':CaptureController()
													game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
												end
											end
										end
									else
										topos(CFrame.new(-10160.787109375, 138.6616973876953, 5955.03076171875))
									end
								end
							else    
								if string.find(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("gravestoneEvent",2), "Error") then
									print("Go to Grave")
									topos(CFrame.new(-8653.2060546875, 140.98487854003906, 6160.033203125))
								elseif string.find(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("gravestoneEvent",2), "Nothing") then
									print("Wait Next Night")
								else
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("gravestoneEvent",2,true)
								end
							end
						end
					else
						topos(CFrame.new(-9681.458984375, 6.139880657196045, 6341.3720703125))
					end
				else
					if _G.soulGuitarhop then
						hop()
					end
				end
			end
		end)
	end
end)

General.newToggle("Auto CDK Quest(Not Working)", "", _G.AutoCdk, function(value)
   _G.AutoCdk = value
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.AutoCdk then
				if GetMaterial("Alucard Fragment") == 0 then
					Auto_Quest_Yama_1 = true
					Auto_Quest_Yama_2 = false
					Auto_Quest_Yama_3 = false
					Auto_Quest_Tushita_1 = false
					Auto_Quest_Tushita_2 = false
					Auto_Quest_Tushita_3 = false
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","Progress","Evil")
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","StartTrial","Evil")
				elseif GetMaterial("Alucard Fragment") == 1 then
					Auto_Quest_Yama_1 = false
					Auto_Quest_Yama_2 = true
					Auto_Quest_Yama_3 = false
					Auto_Quest_Tushita_1 = false
					Auto_Quest_Tushita_2 = false
					Auto_Quest_Tushita_3 = false
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","Progress","Evil")
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","StartTrial","Evil")
				elseif GetMaterial("Alucard Fragment") == 2 then
					Auto_Quest_Yama_1 = false
					Auto_Quest_Yama_2 = false
					Auto_Quest_Yama_3 = true
					Auto_Quest_Tushita_1 = false
					Auto_Quest_Tushita_2 = false
					Auto_Quest_Tushita_3 = false
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","Progress","Evil")
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","StartTrial","Evil")
				elseif GetMaterial("Alucard Fragment") == 3 then
					Auto_Quest_Yama_1 = false
					Auto_Quest_Yama_2 = false
					Auto_Quest_Yama_3 = false
					Auto_Quest_Tushita_1 = true
					Auto_Quest_Tushita_2 = false
					Auto_Quest_Tushita_3 = false
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","Progress","Good")
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","StartTrial","Good")
				elseif GetMaterial("Alucard Fragment") == 4 then
					Auto_Quest_Yama_1 = false
					Auto_Quest_Yama_2 = false
					Auto_Quest_Yama_3 = false
					Auto_Quest_Tushita_1 = false
					Auto_Quest_Tushita_2 = true
					Auto_Quest_Tushita_3 = false
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","Progress","Good")
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","StartTrial","Good")
				elseif GetMaterial("Alucard Fragment") == 5 then
					Auto_Quest_Yama_1 = false
					Auto_Quest_Yama_2 = false
					Auto_Quest_Yama_3 = false
					Auto_Quest_Tushita_1 = false
					Auto_Quest_Tushita_2 = false
					Auto_Quest_Tushita_3 = true
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","Progress","Good")
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","StartTrial","Good")
				elseif GetMaterial("Alucard Fragment") == 6 then
					if game:GetService("Workspace").Enemies:FindFirstChild("Cursed Skeleton Boss [Lv. 2025] [Boss]") or game:GetService("Workspace").ReplicatedStorage:FindFirstChild("Cursed Skeleton Boss [Lv. 2025] [Boss]") then
						Auto_Quest_Yama_1 = false
						Auto_Quest_Yama_2 = false
						Auto_Quest_Yama_3 = false
						Auto_Quest_Tushita_1 = false
						Auto_Quest_Tushita_2 = false
						Auto_Quest_Tushita_3 = false
						if game:GetService("Workspace").Enemies:FindFirstChild("Cursed Skeleton Boss [Lv. 2025] [Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Cursed Skeleton [Lv. 2200]") then
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == "Cursed Skeleton Boss [Lv. 2025] [Boss]" or v.Name == "Cursed Skeleton [Lv. 2200]" then
									if v.Humanoid.Health > 0 then
										v.HumanoidRootPart.CanCollide = false
										v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
										topos(v.HumanoidRootPart.CFrame * CFrame.new(0,50,0))
										game:GetService'VirtualUser':CaptureController()
										game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
									end
								end
							end
						end
					else
						if (CFrame.new(-12361.7060546875, 603.3547973632812, -6550.5341796875).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 100 then
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","Progress","Good")
							wait(1)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","Progress","Evil")
							wait(1)
							topos(CFrame.new(-12361.7060546875, 603.3547973632812, -6550.5341796875))
							wait(1.5)
							game:GetService("VirtualInputManager"):SendKeyEvent(true, "E", false, game)
							wait(1.5)
							topos(CFrame.new(-12253.5419921875, 598.8999633789062, -6546.8388671875))
						else
							topos(CFrame.new(-12361.7060546875, 603.3547973632812, -6550.5341796875))
						end   
					end
				end
			end
		end)
	end
end)

spawn(function()
	while wait() do
		if Auto_Quest_Yama_1 then
			pcall(function()
				if game:GetService("Workspace").Enemies:FindFirstChild("Mythological Pirate [Lv. 1850]") then
					for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
						if v.Name == "Mythological Pirate [Lv. 1850]" then
							repeat wait()
								topos(v.HumanoidRootPart.CFrame * CFrame.new(0,0,-2))
							until _G.AutoCdk == false or Auto_Cursed_Dual_Katana == false or Auto_Quest_Yama_1 == false
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","StartTrial","Evil")
						end
					end
				else
					topos(CFrame.new(-13451.46484375, 543.712890625, -6961.0029296875))
				end
			end)
		end
	end
end)

spawn(function()
	while wait() do
		pcall(function()
			if Auto_Quest_Yama_2 then
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if v:FindFirstChild("HazeESP") then
						v.HazeESP.Size = UDim2.new(50,50,50,50)
						v.HazeESP.MaxDistance = "inf"
					end
				end
				for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
					if v:FindFirstChild("HazeESP") then
						v.HazeESP.Size = UDim2.new(50,50,50,50)
						v.HazeESP.MaxDistance = "inf"
					end
				end
			end
		end)
	end
end)

spawn(function()
	while wait() do
		pcall(function()
			for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
				if Auto_Quest_Yama_2 and v:FindFirstChild("HazeESP") and (v.HumanoidRootPart.Position - PosMonsEsp.Position).magnitude <= 300 then
					v.HumanoidRootPart.CFrame = PosMonsEsp
					v.HumanoidRootPart.CanCollide = false
					v.HumanoidRootPart.Size = Vector3.new(50,50,50)
					if not v.HumanoidRootPart:FindFirstChild("BodyVelocity") then
						local vc = Instance.new("BodyVelocity", v.HumanoidRootPart)
						vc.MaxForce = Vector3.new(1, 1, 1) * math.huge
						vc.Velocity = Vector3.new(0, 0, 0)
					end
				end
			end
		end)
	end
end)

spawn(function()
	while wait() do
		if Auto_Quest_Yama_2 then 
			pcall(function() 
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if v:FindFirstChild("HazeESP") then
						repeat wait()
							if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 2000 then
								topos(y.HumanoidRootPart.CFrameMon * CFrame.new(0,20,0))
							else
								StartMagnet = true
								FastAttack = true
								if Auto_Buso then
									if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
									end
								end
								if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Select_Weapon) then
									wait()
									EquipWeapon(_G.Select_Weapon)
								end
								PosMonsEsp = v.HumanoidRootPart.CFrame
								if not FastAttack then
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								end
								v.HumanoidRootPart.Size = Vector3.new(60,60,60)
								if _G.Configs["Show Hitbox"] then
									v.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
								else
									v.HumanoidRootPart.Transparency = 1
								end
								v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								v.HumanoidRootPart.CanCollide = false
								v.Humanoid:ChangeState(11)
								topos(v.HumanoidRootPart.CFrame * CFrame.new(0,20,0))								
							end      
						until Auto_Cursed_Dual_Katana == false or Auto_Quest_Yama_2 == false or not v.Parent or v.Humanoid.Health <= 0 or not v:FindFirstChild("HazeESP")
					else
						for x,y in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
							if y:FindFirstChild("HazeESP") then
								if (y.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 2000 then
									topos(y.HumanoidRootPart.CFrameMon* CFrame.new(0,20,0))
								else
									topos(y.HumanoidRootPart.CFrame * CFrame.new(0,20,0))
								end
							end
						end
					end
				end
			end)
		end
	end
end)

spawn(function()
	while wait() do
		if Auto_Quest_Yama_3 then
			pcall(function()
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Hallow Essence") then         
					_G.Main["Auto Farm Bone"] = false           
					topos(game:GetService("Workspace").Map["Haunted Castle"].Summoner.Detection.CFrame)
				elseif game:GetService("Workspace").Map:FindFirstChild("HellDimension") then
					repeat wait()
						if game:GetService("Workspace").Enemies:FindFirstChild("Cursed Skeleton [Lv. 2200]") or game:GetService("Workspace").Enemies:FindFirstChild("Cursed Skeleton [Lv. 2200] [Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Hell's Messenger [Lv. 2200] [Boss]") then
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == "Cursed Skeleton [Lv. 2200]" or v.Name == "Cursed Skeleton [Lv. 2200] [Boss]" or v.Name == "Hell's Messenger [Lv. 2200] [Boss]" then
									if v.Humanoid.Health > 0 then
										repeat wait()
											StartMagnet = true
											FastAttack = true
											if Auto_Buso then
												if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
												end
											end
											if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Select_Weapon) then
												wait()
												EquipWeapon(_G.Select_Weapon)
											end
											PosMonsEsp = v.HumanoidRootPart.CFrame
											if not FastAttack then
												game:GetService'VirtualUser':CaptureController()
												game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
											end
											v.HumanoidRootPart.Size = Vector3.new(60,60,60)
											if _G.Configs["Show Hitbox"] then
												v.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
											else
												v.HumanoidRootPart.Transparency = 1
											end
											v.Humanoid.JumpPower = 0
											v.Humanoid.WalkSpeed = 0
											v.HumanoidRootPart.CanCollide = false
											v.Humanoid:ChangeState(11)
											topos(v.HumanoidRootPart.CFrame * CFrame.new(0,50,0))
										until v.Humanoid.Health <= 0 or not v.Parent or Auto_Quest_Yama_3 == false
									end
								end
							end
						else
							wait(5)
							topos(game:GetService("Workspace").Map.HellDimension.Torch1.CFrame)
							wait(1.5)
							game:GetService("VirtualInputManager"):SendKeyEvent(true, "E", false, game)
							wait(1.5)        
							topos(game:GetService("Workspace").Map.HellDimension.Torch2.CFrame)
							wait(1.5)
							game:GetService("VirtualInputManager"):SendKeyEvent(true, "E", false, game)
							wait(1.5)     
							topos(game:GetService("Workspace").Map.HellDimension.Torch3.CFrame)
							wait(1.5)
							game:GetService("VirtualInputManager"):SendKeyEvent(true, "E", false, game)
							wait(1.5)     
							topos(game:GetService("Workspace").Map.HellDimension.Exit.CFrame)
						end
					until Auto_Cursed_Dual_Katana == false or Auto_Quest_Yama_3 == false or GetMaterial("Alucard Fragment") == 3
				else
					if game:GetService("Workspace").Enemies:FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") or game.ReplicatedStorage:FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") then
						if game:GetService("Workspace").Enemies:FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") then
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == "Soul Reaper [Lv. 2100] [Raid Boss]" then
									if v.Humanoid.Health > 0 then
										repeat wait()
											topos(v.HumanoidRootPart.CFrame * CFrame.new(0,0,-2))
										until Auto_Cursed_Dual_Katana == false or Auto_Quest_Yama_3 == false or game:GetService("Workspace").Map:FindFirstChild("HellDimension")
									end
								end
							end
						else
							topos(CFrame.new(-9570.033203125, 315.9346923828125, 6726.89306640625))
						end
					else
						_G.Main["Auto Farm Bone"] = true
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,1)
					end
				end
			end)
		end
	end
end)

spawn(function() 
	while wait() do
		if Auto_Quest_Tushita_1 then
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CDKQuest","BoatQuest",workspace.NPCs:FindFirstChild("Luxury Boat Dealer"))
		end
	end
end)

spawn(function()
	while wait() do
		if Auto_Quest_Tushita_1 then
			topos(CFrame.new(-9546.990234375, 21.139892578125, 4686.1142578125))
			wait(5)
			topos(CFrame.new(-6120.0576171875, 16.455780029296875, -2250.697265625))
			wait(5)
			topos(CFrame.new(-9533.2392578125, 7.254445552825928, -8372.69921875))    
		end
	end
end)

spawn(function()
	while wait() do
		if Auto_Quest_Tushita_2 then
			pcall(function()
				if (CFrame.new(-5539.3115234375, 313.800537109375, -2972.372314453125).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
					for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
						if Auto_Quest_Tushita_2 and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
							if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude < 2000 then
								repeat wait()
									v.HumanoidRootPart.CanCollide = false
									v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
									topos(v.HumanoidRootPart.CFrame * CFrame.new(0,50,0))
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								until v.Humanoid.Health <= 0 or not v.Parent or Auto_Quest_Tushita_2 == false
							end
						end
					end
				else
					topos(CFrame.new(-5545.1240234375, 313.800537109375, -2976.616455078125))
				end
			end)
		end
	end
end)

spawn(function()
	while wait() do
		if Auto_Quest_Tushita_3 then
			pcall(function()
				if game:GetService("Workspace").Enemies:FindFirstChild("Cake Queen [Lv. 2175] [Boss]") or game.ReplicatedStorage:FindFirstChild("Cake Queen [Lv. 2175] [Boss]") then
					if game:GetService("Workspace").Enemies:FindFirstChild("Cake Queen [Lv. 2175] [Boss]") then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if v.Name == "Cake Queen [Lv. 2175] [Boss]" then
								if v.Humanoid.Health > 0 then
									repeat wait()
										if Auto_Buso then
											if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
											end
										end
										if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Select_Weapon) then
											wait()
											EquipWeapon(_G.Select_Weapon)
										end
										if not FastAttack then
											game:GetService'VirtualUser':CaptureController()
											game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										end
										v.HumanoidRootPart.Size = Vector3.new(60,60,60)
										if _G.Configs["Show Hitbox"] then
											v.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
										else
											v.HumanoidRootPart.Transparency = 1
										end
										v.Humanoid.JumpPower = 0
										v.Humanoid.WalkSpeed = 0
										v.HumanoidRootPart.CanCollide = false
										v.Humanoid:ChangeState(11)
										topos(v.HumanoidRootPart.CFrame * CFrame.new(0,50,0))
									until Auto_Cursed_Dual_Katana == false or Auto_Quest_Tushita_3 == false or game:GetService("Workspace").Map:FindFirstChild("HeavenlyDimension")
								end
							end
						end
					else
						topos(CFrame.new(-709.3132934570312, 381.6005859375, -11011.396484375))
					end
				elseif game:GetService("Workspace").Map:FindFirstChild("HeavenlyDimension") then
					repeat wait()
						if game:GetService("Workspace").Enemies:FindFirstChild("Cursed Skeleton [Lv. 2200]") or game:GetService("Workspace").Enemies:FindFirstChild("Cursed Skeleton [Lv. 2200] [Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Heaven's Guardian [Lv. 2200] [Boss]") then
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == "Cursed Skeleton [Lv. 2200]" or v.Name == "Cursed Skeleton [Lv. 2200] [Boss]" or v.Name == "Heaven's Guardian [Lv. 2200] [Boss]" then
									if v.Humanoid.Health > 0 then
										repeat wait()
											if Auto_Buso then
												if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
												end
											end
											if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Select_Weapon) then
												wait()
												EquipWeapon(_G.Select_Weapon)
											end
											if not FastAttack then
												game:GetService'VirtualUser':CaptureController()
												game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
											end
											v.HumanoidRootPart.Size = Vector3.new(60,60,60)
											if _G.Configs["Show Hitbox"] then
												v.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
											else
												v.HumanoidRootPart.Transparency = 1
											end
											v.Humanoid.JumpPower = 0
											v.Humanoid.WalkSpeed = 0
											v.HumanoidRootPart.CanCollide = false
											v.Humanoid:ChangeState(11)
										until v.Humanoid.Health <= 0 or not v.Parent or Auto_Quest_Tushita_3 == false
									end
								end
							end
						else
							wait(5)
							topos(game:GetService("Workspace").Map.HeavenlyDimension.Torch1.CFrame)
							wait(1.5)
							game:GetService("VirtualInputManager"):SendKeyEvent(true, "E", false, game)
							wait(1.5)        
							topos(game:GetService("Workspace").Map.HeavenlyDimension.Torch2.CFrame)
							wait(1.5)
							game:GetService("VirtualInputManager"):SendKeyEvent(true, "E", false, game)
							wait(1.5)     
							topos(game:GetService("Workspace").Map.HeavenlyDimension.Torch3.CFrame)
							wait(1.5)
							game:GetService("VirtualInputManager"):SendKeyEvent(true, "E", false, game)
							wait(1.5)     
							topos(game:GetService("Workspace").Map.HeavenlyDimension.Exit.CFrame)
						end
					until Auto_Cursed_Dual_Katana == false or Auto_Quest_Tushita_3 == false or GetMaterial("Alucard Fragment") == 6
				else
					hop()
				end
			end)
		end
	end
end)

General.newToggle("Auto Buy Enchancement", "", _G.Auto_Buy_Enchancement, function(value)
   _G.Auto_Buy_Enchancement = value
	StopTween(_G.Auto_Buy_Enchancement)
end)

spawn(function()
	while wait() do
		if _G.Auto_Buy_Enchancement then
			local args = {
				[1] = "ColorsDealer",
				[2] = "2"
			}
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
		end 
	end
end)

General.newToggle("Auto Rengoku", "ออโต้ทำดาบเรนโก", _G.Auto_Rengoku, function(value)
    _G.Auto_Rengoku = value
	StopTween(_G.Auto_Rengoku)
end)

spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function()
		pcall(function()
			for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
				if _G.Auto_Rengoku and StartRengokuStartMagnet and (v.Name == "Snow Lurker [Lv. 1375]" or v.Name == "Arctic Warrior [Lv. 1350]") and (v.HumanoidRootPart.Position - RengokuMon.Position).magnitude <= 350 then
					v.HumanoidRootPart.CFrame = RengokuMon
					v.HumanoidRootPart.CanCollide = false
					v.HumanoidRootPart.Size = Vector3.new(50,50,50)
					if v.Humanoid:FindFirstChild("Animator") then
						v.Humanoid.Animator:Destroy()
					end
					sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
				end
			end
		end)
	end)
end)

spawn(function()
	while wait() do
		if _G.Auto_Rengoku then
			pcall(function()
				if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Hidden Key") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Hidden Key") then
					EquipWeapon("Hidden Key")
					topos(CFrame.new(6571.1201171875, 299.23028564453, -6967.841796875))
				elseif game:GetService("Workspace").Enemies:FindFirstChild("Snow Lurker [Lv. 1375]") or game:GetService("Workspace").Enemies:FindFirstChild("Arctic Warrior [Lv. 1350]") then
					for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
						if (v.Name == "Snow Lurker [Lv. 1375]" or v.Name == "Arctic Warrior [Lv. 1350]") and v.Humanoid.Health > 0 then
							repeat wait()
								AutoHaki()
								EquipWeapon(_G.Select_Weapon)
								v.HumanoidRootPart.CanCollide = false
								v.HumanoidRootPart.Size = Vector3.new(50,50,50)
								RengokuMon = v.HumanoidRootPart.CFrame
								topos(v.HumanoidRootPart.CFrame * MethodFarm)
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								StartRengokuStartMagnet = true
							until game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Hidden Key") or _G.Auto_Rengoku == false or not v.Parent or v.Humanoid.Health <= 0
							StartRengokuStartMagnet = false
						end
					end
				else
					StartRengokuStartMagnet = false
					topos(CFrame.new(5439.716796875, 84.420944213867, -6715.1635742188))
				end
			end)
		end
	end
end)

General.newToggle("Auto Buddy Sword", "", _G.AutoBudySword, function(value)
   _G.AutoBudySword = value
		StopTween(_G.AutoBudySword)
end)

General.newToggle("Auto Buddy Sword Hop", "", _G.AutoBudySwordHop, function(value)
    _G.AutoBudySwordHop = value
end)

spawn(function()
		while wait() do
			if _G.AutoBudySword then
				pcall(function()
					if game:GetService("Workspace").Enemies:FindFirstChild("Cake Queen [Lv. 2175] [Boss]") then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if v.Name == "Cake Queen [Lv. 2175] [Boss]" then
								if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
									repeat task.wait()
										AutoHaki()
										EquipWeapon(_G.SelectWeapon)
										v.HumanoidRootPart.CanCollide = false
										v.Humanoid.WalkSpeed = 0
										v.HumanoidRootPart.Size = Vector3.new(55,55,55)
										TP(v.HumanoidRootPart.CFrame * MethodFarm)                         
										game:GetService("VirtualUser"):CaptureController()
										game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
										sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
									until not _G.AutoBudySword or not v.Parent or v.Humanoid.Health <= 0
								end
							end
						end
					else
						if game:GetService("ReplicatedStorage"):FindFirstChild("Cake Queen [Lv. 2175] [Boss]") then
							TP(game:GetService("ReplicatedStorage"):FindFirstChild("Cake Queen [Lv. 2175] [Boss]").HumanoidRootPart.CFrame * MethodFarm)
						else
							if _G.AutoBudySwordHop then
								Hop()
							end
						end
					end
				end)
			end
		end
	end)
end

General.newToggle("Auto Hallow Scythe", "", _G.AutoFarmBossHallow, function(value)
   _G.AutoFarmBossHallow = value
		StopTween(_G.AutoFarmBossHallow)
end)

General.newToggle("Auto Hallow Scythe Hop", "", _G.AutoFarmBossHallowHop, function(value)
   _G.AutoFarmBossHallowHop = value
end)

spawn(function()
		while wait() do
			if _G.AutoFarmBossHallow then
				pcall(function()
					if game:GetService("Workspace").Enemies:FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if string.find(v.Name , "Soul Reaper") then
								repeat task.wait()
									EquipWeapon(_G.SelectWeapon)
									AutoHaki()
									v.HumanoidRootPart.Size = Vector3.new(50,50,50)
									TP(v.HumanoidRootPart.CFrame * MethodFarm)
									game:GetService("VirtualUser"):CaptureController()
									game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 670))
									v.HumanoidRootPart.Transparency = 1
									sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
								until v.Humanoid.Health <= 0 or _G.AutoFarmBossHallow == false
							end
						end
					elseif game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Hallow Essence") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Hallow Essence") then
						repeat TP(CFrame.new(-8932.322265625, 146.83154296875, 6062.55078125)) wait() until (CFrame.new(-8932.322265625, 146.83154296875, 6062.55078125).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 8                        
					else
						if game:GetService("ReplicatedStorage"):FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") then
							TP(game:GetService("ReplicatedStorage"):FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(5,10,7))
						else
							if _G.AutoFarmBossHallowHop then
								Hop()
							end
						end
					end
				end)
			end
		end
	end)
end

General.newToggle("Auto Dark Dagger", "", _G.AutoDarkDagger, function(value)
    _G.AutoDarkDagger = value
		StopTween(_G.AutoDarkDagger)
end)

spawn(function()
		pcall(function()
			while wait() do
				if _G.AutoDarkDagger then
					if game:GetService("Workspace").Enemies:FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("rip_indra [Lv. 5000] [Raid Boss]") then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if v.Name == ("rip_indra True Form [Lv. 5000] [Raid Boss]" or v.Name == "rip_indra [Lv. 5000] [Raid Boss]") and v.Humanoid.Health > 0 and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") then
								repeat task.wait()
									pcall(function()
										AutoHaki()
										EquipWeapon(_G.SelectWeapon)
										v.HumanoidRootPart.CanCollide = false
										v.HumanoidRootPart.Size = Vector3.new(50,50,50)
										TP(v.HumanoidRootPart.CFrame * MethodFarm)
										game:GetService("VirtualUser"):CaptureController()
										game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 670),workspace.CurrentCamera.CFrame)
									end)
								until _G.AutoDarkDagger == false or v.Humanoid.Health <= 0
							end
						end
					end
				end
			end
		end)
	end)


General.newToggle("Auto Dark Dagger Hop", "", _G.AutoDarkDagger_Hop, function(value)
    _G.AutoDarkDagger_Hop = value
end)

spawn(function()
		pcall(function()
			while wait() do
				if (_G.AutoDarkDagger_Hop and _G.AutoDarkDagger) and World3 and not game:GetService("ReplicatedStorage"):FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") and not game:GetService("Workspace").Enemies:FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") then
					Hop()
				end
			end
		end)
	end)
end

Dungeon.newToggle("Auto Farm Dungeon", "ไปซื้อชิพดันที่อยากลงก่อนเพราะสคริปตนี้ไม่มีดรอปดราวน์", _G.Auto_Raid, function(value)
  _G.Auto_Raid = value
	StopTween(_G.Auto_Raid)
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.Auto_Raid or _G.Auto_Next then
				if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Timer.Visible == true then
					if game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") then
						topos(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame*CFrame.new(0,30,0))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") then
						topos(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").CFrame*CFrame.new(0,30,0))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") then
						topos(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").CFrame*CFrame.new(0,30,0))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") then
						topos(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").CFrame*CFrame.new(0,30,0))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
						topos(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").CFrame*CFrame.new(0,30,0))
					end
				end
			end
		end
	end)
end)

General.newToggle("Kill Aura เปิดตอนเข้าดัน ", "", _G.Kill, function(value)
    _G.Kill = value
end)

spawn(function()
	pcall(function() 
		while wait() do
			if _G.Auto_Raid or _G.Kill then
				if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Timer.Visible == true then
					for i,v in pairs(game:GetService("Workspace").Enemies:GetDescendants()) do
						if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
							pcall(function()
								repeat task.wait()                                    
									v.Humanoid.Health = 0
									v.HumanoidRootPart.CanCollide = false
									sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
								until not _G.Auto_Dungeon and _G.kill or not v.Parent or v.Humanoid.Health <= 0
							end)
						end
					end
				end
			end
		end
	end)
end)

General.newToggle("Auto Next Island ", "ออโต้ออกเกาะ", _G.Auto_Next, function(value)
   _G.Auto_Next = value
	StopTween(_G.Auto_Next)
end)

General.newToggle("Auto Select Dungeon", "", _G.AutoSelectDungeon, function(value)
   _G.AutoSelectDungeon = value
end)

spawn(function()
	while wait() do
		if _G.AutoSelectDungeon then
			pcall(function()
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flame-Flame") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flame-Flame") then
					_G.SelectChip = "Flame"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Ice-Ice") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Ice-Ice") then
					_G.SelectChip = "Ice"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Quake-Quake") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Quake-Quake") then
					_G.SelectChip = "Quake"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Light-Light") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Light-Light") then
					_G.SelectChip = "Light"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dark-Dark") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dark-Dark") then
					_G.SelectChip = "Dark"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("String-String") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("String-String") then
					_G.SelectChip = "String"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Rumble-Rumble") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Rumble-Rumble") then
					_G.SelectChip = "Rumble"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Magma-Magma") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Magma-Magma") then
					_G.SelectChip = "Magma"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Human-Human: Buddha Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Human-Human: Buddha Fruit") then
					_G.SelectChip = "Human: Buddha"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Sand-Sand") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Sand-Sand") then
					_G.SelectChip = "Sand"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Bird-Bird: Phoenix") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Bird-Bird: Phoenix") then
					_G.SelectChip = "Bird: Phoenix"
				elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dough-Dough") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dough-Dough") then
					_G.SelectChip = "Dough"
				else
					_G.SelectChip = "Flame"
				end
			end)
		end
	end
end)

General.newToggle("Auto Buy Chip ", "ออโต้ซื้อชิพดัน", _G.AutoBuyChip, function(value)
    _G.AutoBuyChip = value
end)

General.newToggle("Auto Start Raid ", "ออโต้เริ่มดัน", true, function(value)
    _G.Auto_StartRaid = value
end)

spawn(function()
	pcall(function()
		while wait() do
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Special Microchip") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Special Microchip") then
				if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
					if _G.Auto_StartRaid then
						if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Timer.Visible == false then
							if World2 then
								fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon2.Button.Main.ClickDetector)
							elseif World3 then
								fireclickdetector(game:GetService("Workspace").Map["Boat Castle"].RaidSummon2.Button.Main.ClickDetector)
							end
						end
					end
				end
			else
				if _G.AutoBuyChip then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("RaidsNpc", "Select", _G.SelectChip)
				end
			end
		end
	end)
end)

DevilFruit.newToggle("Auto Eat Fruit", "ออโต้กินผล", _G.AutoEatFruit, function(value)
  _G.AutoEatFruit = value
end)

spawn(function()
	pcall(function()
		while wait(.1) do
			if _G.AutoEatFruit then
				game:GetService("Players").LocalPlayer.Character:FindFirstChild(_G.SelectFruitEat).EatRemote:InvokeServer()
			end
		end
	end)
end)

DevilFruit.newToggle("Auto Eat Fruit Hop", "", _G.AutoEatFruitHop, function(value)
    _G.AutoEatFruitHop = value
end)

spawn(function()
	pcall(function()
		while wait(.1) do wait(10)
			if _G.AutoEatFruitHop and _G.SelectFruitEat ~= nil then
				if not game:GetService("Players").LocalPlayer.Character:FindFirstChild(_G.SelectFruitEat) or not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(_G.SelectFruitEat) then
					Hop()
				else
					game:GetService("Players").LocalPlayer.Character:FindFirstChild(_G.SelectFruitEat).EatRemote:InvokeServer()
				end
			end
		end
	end)
end)

spawn(function()
	pcall(function()
		while wait(.1) do
			if _G.AutoBuyFruitSniper then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("GetFruits")
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PurchaseRawFruit",_G.SelectFruit)
			end 
		end
	end)
end)

DevilFruit.newToggle("Auto Random Fruit", "ออโต้สุ่มผล", _G.Random_Auto, function(value)
   _G.Random_Auto = value
end)

spawn(function()
	pcall(function()
		while wait(.1) do
			if _G.Random_Auto then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin","Buy")
			end 
		end
	end)
end)

DevilFruit.newButton("Random Fruit", "สุ่มผล", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin","Buy")
end)

DevilFruit.newToggle("Auto Drop Fruit", "ออโต้ทิ้งผล", _G.DropFruit, function(value)
    _G.DropFruit = value
end)

spawn(function()
	while wait() do
		if _G.DropFruit then
			pcall(function()
				for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
					if string.find(v.Name, "Fruit") then
						EquipWeapon(v.Name)
						wait(.1)
						if game:GetService("Players").LocalPlayer.PlayerGui.Main.Dialogue.Visible == true then
							game:GetService("Players").LocalPlayer.PlayerGui.Main.Dialogue.Visible = false
						end
						EquipWeapon(v.Name)
						game:GetService("Players").LocalPlayer.Character:FindFirstChild(SelectFruit).EatRemote:InvokeServer("Drop")
					end
				end
				for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
					if string.find(v.Name, "Fruit") then
						EquipWeapon(v.Name)
						wait(.1)
						if game:GetService("Players").LocalPlayer.PlayerGui.Main.Dialogue.Visible == true then
							game:GetService("Players").LocalPlayer.PlayerGui.Main.Dialogue.Visible = false
						end
						EquipWeapon(v.Name)
						game:GetService("Players").LocalPlayer.Character:FindFirstChild(SelectFruit).EatRemote:InvokeServer("Drop")
					end
				end
			end)
		end
	end
end)

DevilFruit.newToggle("Auto Store Fruit", "ออโต้เก็บผล", _G.AutoStoreFruit, function(value)
    _G.AutoStoreFruit = value
end)

spawn(function()
	pcall(function()
		while wait(.1) do
			if _G.AutoStoreFruit then
				for i,v in pairs(FruitList) do
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit",v)
				end
			end
		end
	end)
end)

DevilFruit.newToggle("Grab Fruit", "", _G.BringFruit, function(value)
    _G.BringFruit = value
	pcall(function()
		while _G.BringFruit do wait(.1)
			for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
				if v:IsA("Tool") then
					local OldCFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame				
					game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Handle.CFrame * CFrame.new(0,0,8)
					v.Handle.CFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame
					wait(.1)
					game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = OldCFrame
				end
			end
		end
	end)
end)

Shop.newButton("Buy Geppo [ $10,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Geppo")
end)

Shop.newButton("Buy Buso Haki [ $25,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Buso")
end)

Shop.newButton("Buy Soru [ $25,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Soru")
end)

Shop.newButton("Buy Observation Haki [ $750,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("KenTalk","Buy")
end)

General.newToggle("Auto Buy Abilities", "", false, function(value)
    Abilities = t
	while Abilities do wait(.1)
		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Geppo")
		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Buso")
		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Soru")
	end
end)

Shop.newButton("Buy Boat", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBoat",_G.SelectBoat)
end)

Shop.newButton("Buy Black Leg [ $150,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
end)

Shop.newButton("Buy Electro [ $550,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
end)

Shop.newButton("Buy Fishman Karate [ $750,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
end)

Shop.newButton("Buy Dragon Claw [ $1,500 Fragments ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","1")
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2")
end)

Shop.newButton("Buy Superhuman [ $3,000,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
end)

Shop.newButton("Buy Death Step [ $5,000 Fragments $5,000,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
end)

Shop.newButton("Buy Sharkman Karate [ $5,000 Fragments $2,500,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate",true)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
end)

Shop.newButton("Buy Electric Claw [ $5,000 Fragments $3,000,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
end)

Shop.newButton("Buy Dragon Talon [ $5,000 Fragments $3,000,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
end)

Shop.newButton("Buy God Human [ $5,000 Fragments $5,000,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman")
end)

Shop.newButton("Cutlass [ $1,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Cutlass")
end)

Shop.newButton("Katana [ $1,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Katana")
end)

Shop.newButton("Iron Mace [ $25,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Iron Mace")
end)

Shop.newButton("Dual Katana [ $12,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Duel Katana")
end)

Shop.newButton("Triple Katana [ $60,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Triple Katana")
end)

Shop.newButton("Pipe [ $100,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Pipe")
end)

Shop.newButton("Dual-Headed Blade [ $400,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Dual-Headed Blade")
end)

Shop.newButton("Bisento [ $1,200,000 Beli ", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Bisento")
end)

Shop.newButton("Soul Cane [ $750,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Soul Cane")
end)

Shop.newButton("Pole v.2 [ 5,000 Fragments ]", "", function()
    game.ReplicatedStorage.Remotes.CommF_:InvokeServer("ThunderGodTalk")
end)

Shop.newButton("Yama Sword [ Elite Hunter 30 ]", "", function()
    _G.AutoYama = value
end)

spawn(function()
	while wait() do
		if _G.AutoYama then
			if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter","Progress") >= 30 then
				repeat wait(.1)
					fireclickdetector(game:GetService("Workspace").Map.Waterfall.SealedKatana.Handle.ClickDetector)
				until game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Yama") or not _G.AutoYama
			end
		end
	end
end)

Shop.newButton("Slingshot [ $5,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Slingshot")
end)

Shop.newButton("Musket [ $8,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Musket")
end)

Shop.newButton("Flintlock [ $10,500 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Flintlock")
end)

Shop.newButton("Refined Slingshot [ $30,000 Beli ]", "", function()
   game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Refined Flintlock")
end)

Shop.newButton("Refined Flintlock [ $65,000 Beli ]", "", function()
    local args = {
		[1] = "BuyItem",
		[2] = "Refined Flintlock"
	}
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

Shop.newButton("Cannon [ $100,000 Beli ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Cannon")
end)

Shop.newButton("Kabucha [ 1,500 Fragments]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Slingshot","1")
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Slingshot","2")
end)

Shop.newButton("Bizarre Rifle [ 250 Ectoplasm ]", "", function()
    local A_1 = "Ectoplasm"
	local A_2 = "Buy"
	local A_3 = 1
	local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
	Event:InvokeServer(A_1, A_2, A_3) 
	local A_1 = "Ectoplasm"
	local A_2 = "Buy"
	local A_3 = 1
	local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
	Event:InvokeServer(A_1, A_2, A_3)
end)

Shop.newButton("Buy Surprise [ $50 Bone ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,1)
end)

Shop.newButton("Stat Refund [ $50 Bone ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,2)
end)

Shop.newButton("Race Reroll [ $50 Bone ]", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,3)
end)

Shop.newButton("Reset Stats (Use 2.5K Fragments)", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Refund","1")
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Refund","2")
end)

Shop.newButton("Random Race (Use 3K Fragments)", "", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Reroll","1")
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Reroll","2")
end)

Shop.newButton("Black Cape [ $50,000 Beli ]", "", function()
    local args = {
		[1] = "BuyItem",
		[2] = "Black Cape"
	}
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

Shop.newButton("Swordsman Hat [ 150k Beli ]", "", function()
    	local args = {
		[1] = "BuyItem",
		[2] = "Swordsman Hat"
	}
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

Shop.newButton("Tomoe Ring [ $500k Beli ]", "", function()
    local args = {
		[1] = "BuyItem",
		[2] = "Tomoe Ring"
	}
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

ESP.newToggle("ESP Player", "", ESPPlayer, function(value)
        ESPPlayer = value
        while ESPPlayer do wait()
            UpdateEspPlayer()
        end
    end)

ESP.newToggle("ESP Chest", "", ChestESP, function(value)
        ChestESP = value
        while ChestESP do wait()
            UpdateChestEsp() 
        end
    end)
    
ESP.newToggle("ESP Fruit", "", DevilFruitESP, function(value)
        DevilFruitESP = value
        while DevilFruitESP do wait()
            UpdateBfEsp() 
        end
    end)
    
ESP.newToggle("ESP Flower", "", FlowerESP, function(value)
        FlowerESP = value
        while FlowerESP do wait()
            UpdateFlowerEsp() 
        end
    end)
    
ESP.newToggle("ESP Island", "", IslandESP, function(value)
        IslandESP = value
        while IslandESP do wait()
            UpdateIslandESP() 
        end
    end)

local x2Code = {
	"3BVISITS",
	"UPD16",
	"FUDD10",
	"BIGNEWS",
	"THEGREATACE",
	"SUB2GAMERROBOT_EXP1",
	"StrawHatMaine",
	"Sub2OfficialNoobie",
	"SUB2NOOBMASTER123",
	"Sub2Daigrock",
	"Axiore",
	"TantaiGaming",
	"STRAWHATMAINE",
	"Enyu_is_Pro",
	"Sub2Fer999",
	"Bluxxy",
	"JCWK",
	"Magicbus",
	"Starcodeheo",
	"SUB2UNCLEKIZARU"
}

Misc.newButton("Redeem All Codes", "ใส่โค้ดทั้งหมด", function()
    function RedeemCode(value)
		game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(value)
	end
	for i,v in pairs(x2Code) do
		RedeemCode(v)
	end
end)

Misc.newToggle("Infinite Energy", "", false, function(value)
    InfiniteEnergy = value
	originalstam = LocalPlayer.Character.Energy.Value
end)

local LocalPlayer = game:GetService'Players'.LocalPlayer
local originalstam = LocalPlayer.Character.Energy.Value
function infinitestam()
	LocalPlayer.Character.Energy.Changed:connect(function()
		if InfinitsEnergy then
			LocalPlayer.Character.Energy.Value = originalstam
		end 
	end)
end
spawn(function()
	while wait(.1) do
		if InfinitsEnergy then
			wait(0.3)
			originalstam = LocalPlayer.Character.Energy.Value
			infinitestam()
		end
	end
end)

Misc.newToggle("Infinite Ability", "", false, function(infA)
    if infA then
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
		Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
	else
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
	end
end)

Misc.newToggle("Infinite Obversation Range", "", getgenv().InfiniteObRange, function(value)
    getgenv().InfiniteObRange = value
	local VS = game:GetService("Players").LocalPlayer.VisionRadius.Value
	while getgenv().InfiniteObRange do
		wait()
		local player = game:GetService("Players").LocalPlayer
		local char = player.Character
		local VisionRadius = player.VisionRadius
		if player then
			if char.Humanoid.Health <= 0 then 
				wait(5) 
			end
			VisionRadius.Value = math.huge
		elseif getgenv().InfiniteObRange == false and player then
			VisionRadius.Value = VS
		end
	end
end)

Misc.newToggle("Infinite Geppo", "", getgenv().InfGeppo, function(value)
    getgenv().InfGeppo = value
end)

spawn(function()
	while wait() do
		pcall(function()
			if getgenv().InfGeppo then
				for i,v in next, getgc() do
					if game:GetService("Players").LocalPlayer.Character.Geppo then
						if typeof(v) == "function" and getfenv(v).script == game:GetService("Players").LocalPlayer.Character.Geppo then
							for i2,v2 in next, getupvalues(v) do
								if tostring(i2) == "9" then
									repeat wait(.1)
										setupvalue(v,i2,0)
									until not getgenv().InfGeppo or game:GetService("Players").LocalPlayer.Character.Humanoid.Health <= 0 
								end
							end
						end
					end
				end
			end
		end)
	end
end)


Misc.newToggle("Infinite Soru", "", getgenv().InfSoru, function(value)
    	getgenv().InfSoru = value
end)

spawn(function()
	while wait() do
		pcall(function()
			if getgenv().InfSoru and game:GetService("Players").LocalPlayer.Character:FindFirstChild("HumanoidRootPart") ~= nil  then
				for i,v in next, getgc() do
					if game:GetService("Players").LocalPlayer.Character.Soru then
						if typeof(v) == "function" and getfenv(v).script == game:GetService("Players").LocalPlayer.Character.Soru then
							for i2,v2 in next, getupvalues(v) do
								if typeof(v2) == "table" then
									repeat wait(.1)
										v2.LastUse = 0
									until not getgenv().InfSoru or game:GetService("Players").LocalPlayer.Character.Humanoid.Health <= 0
								end
							end
						end
					end
				end
			end
		end)
	end
end)

Misc.newButton("Infinite Jump", "", function(value)
    Infinite = State
	game:GetService("UserInputService").JumpRequest:connect(function()
		if Infinite then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
		end
	end) 
end)

Misc.newToggle("Show Chat disabled", "", _G.chat, function(value)
    _G.chat = value
	if _G.chat == true then
		local StarterGui = game:GetService('StarterGui')
		StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Chat, false)    
	elseif _G.chat == false then
		local StarterGui = game:GetService('StarterGui')
		StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Chat, true)    
	end
end)

Misc.newToggle("Show leaderboard disabled", "", _G.leaderboard, function(value)
    _G.leaderboard = a
	if _G.leaderboard == true then
		local StarterGui = game:GetService('StarterGui')
		game:GetService('StarterGui'):SetCoreGuiEnabled(Enum.CoreGuiType.PlayerList, false)   
	elseif _G.leaderboard == false then
		local StarterGui = game:GetService('StarterGui')
		game:GetService('StarterGui'):SetCoreGuiEnabled(Enum.CoreGuiType.PlayerList, true)   
	end
end)

Misc.newToggle("Highlight Mode", "", false, function(value)
    if value == true then
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Beli.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.HP.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Energy.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.StatsButton.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ShopButton.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Skills.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Level.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.MenuButton.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Code.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Settings.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Mute.Visible = false
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.CrewButton.Visible = false
	else
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Beli.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.HP.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Energy.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.StatsButton.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ShopButton.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Skills.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Level.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.MenuButton.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Code.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Settings.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Mute.Visible = true
		game:GetService("Players")["LocalPlayer"].PlayerGui.Main.CrewButton.Visible = true
	end
end)

Misc.newToggle("Graphic", "", false, function(value)
    if v then
		getgenv().mode = "Autumn" -- Choose from Summer and Autumn
		local a = game.Lighting
		a.Ambient = Color3.fromRGB(33, 33, 33)
		a.Brightness = 0.3
		a.ColorShift_Bottom = Color3.fromRGB(0, 0, 0)
		a.ColorShift_Top = Color3.fromRGB(255, 247, 237)
		a.EnvironmentDiffuseScale = 0.105
		a.EnvironmentSpecularScale = 0.522
		a.GlobalShadows = true
		a.OutdoorAmbient = Color3.fromRGB(51, 54, 67)
		a.ShadowSoftness = 0.04
		a.GeographicLatitude = -15.525
		a.ExposureCompensation = 0.75
		local b = Instance.new("BloomEffect", a)
		b.Name = "BloomEffect_Graphic"
		b.Enabled = true
		b.Intensity = 0.04
		b.Size = 1900
		b.Threshold = 0.915
		local c = Instance.new("ColorCorrectionEffect", a)
		c.Name = 'ColorCorrectionEffect1_Graphic'
		c.Brightness = 0.176
		c.Contrast = 0.39
		c.Enabled = true
		c.Saturation = 0.2
		c.TintColor = Color3.fromRGB(217, 145, 57)
		if getgenv().mode == "Summer" then
			c.TintColor = Color3.fromRGB(255, 220, 148)
		elseif getgenv().mode == "Autumn" then
			c.TintColor = Color3.fromRGB(242, 193, 79)
		end
		local d = Instance.new("DepthOfFieldEffect", Graphic)
		d.Name =  'DepthOfFieldEffect_Graphic'
		d.Enabled = true
		d.FarIntensity = 0.077
		d.FocusDistance = 21.54
		d.InFocusRadius = 20.77
		d.NearIntensity = 0.277
		local e = Instance.new("ColorCorrectionEffect", a)
		e.Name = 'ColorCorrectionEffect2_Graphic'
		e.Brightness = 0
		e.Contrast = -0.07
		e.Saturation = 0
		e.Enabled = true
		e.TintColor = Color3.fromRGB(255, 247, 239)
		local e2 = Instance.new("ColorCorrectionEffect", a)
		e2.Name = 'ColorCorrectionEffect3_Graphic'
		e2.Brightness = 0.2
		e2.Contrast = 0.45
		e2.Saturation = -0.1
		e2.Enabled = true
		e2.TintColor = Color3.fromRGB(255, 255, 255)
		local s = Instance.new("SunRaysEffect", a)
		s.Name = 'SunRaysEffect_Graphic'
		s.Enabled = false
		s.Intensity = 0.01
		s.Spread = 0.146
	else
		local a = game.Lighting
		a.Ambient = Color3.fromRGB(170, 170, 170)
		a.Brightness = 2
		a.ColorShift_Bottom = Color3.fromRGB(0, 0, 0)
		a.ColorShift_Top = Color3.fromRGB(0, 0, 0)
		a.EnvironmentDiffuseScale = 0.105
		a.EnvironmentSpecularScale = 0.522
		a.GlobalShadows = false
		a.OutdoorAmbient = Color3.fromRGB(127, 127, 127)
		a.ShadowSoftness = 0
		a.GeographicLatitude = 66
		a.ExposureCompensation = 0.2
		game:GetService("Lighting")["BloomEffect_Graphic"]:Destroy()
		game:GetService("Lighting")["ColorCorrectionEffect1_Graphic"]:Destroy()
		game:GetService("Lighting")["ColorCorrectionEffect2_Graphic"]:Destroy()
		game:GetService("Lighting")["ColorCorrectionEffect3_Graphic"]:Destroy()
		game:GetService("Lighting")["SunRaysEffect_Graphic"]:Destroy()
	end
end)

Misc.newToggle("Xray", "", false, function(value)
    NoWorld = value
	if NoWorld == true then
		transparent = true
		x(transparent)
	elseif NoWorld == false then
		transparent = false
		x(transparent)
	end
end)

local transparent = false -- xray
function x(v)
	if v then
		for _,i in pairs(workspace:GetDescendants()) do
			if i:IsA("BasePart") and not i.Parent:FindFirstChild("Humanoid") and not i.Parent.Parent:FindFirstChild("Humanoid") then
				i.LocalTransparencyModifier = 0.7
			end
		end
	else
		for _,i in pairs(workspace:GetDescendants()) do
			if i:IsA("BasePart") and not i.Parent:FindFirstChild("Humanoid") and not i.Parent.Parent:FindFirstChild("Humanoid") then
				i.LocalTransparencyModifier = 0
			end
		end
	end
end

---- [RainbowHaki]
spawn(function()
	while wait() do
		if RainbowHaki then
			pcall(function()
				if game.Players.LocalPlayer.Character.HasBuso then
					for i,v in pairs(game.Players.LocalPlayer.Character.Humanoid:GetChildren()) do
						if v.Name == "RightLowerArm_BusoLayer1" or v.Name == "RightLowerArm_BusoLayer2" or v.Name == "RightHand_BusoLayer1" or v.Name == "RightHand_BusoLayer2" or v.Name == "LeftLowerArm_BusoLayer1" or v.Name == "LeftLowerArm_BusoLayer2" or v.Name == "LeftHand_BusoLayer1" or v.Name == "LeftHand_BusoLayer2" or v.Name == "LeftHand_BusoLayer1" or v.Name == "RightUpperArm_BusoLayer1" or v.Name == "RightUpperArm_BusoLayer2" or v.Name == "LeftUpperArm_BusoLayer1" or v.Name == "LeftUpperArm_BusoLayer2" or v.Name == "UpperTorso_BusoLayer1" or v.Name == "UpperTorso_BusoLayer2" or v.Name == "LowerTorso_BusoLayer1" or v.Name == "LowerTorso_BusoLayer2" or v.Name == "Head_BusoLayer1" or v.Name == "Head_BusoLayer2" or v.Name == "RightUpperLeg_BusoLayer1" or v.Name == "RightUpperLeg_BusoLayer2" or v.Name == "LeftUpperLeg_BusoLayer1" or v.Name == "LeftUpperLeg_BusoLayer2" or v.Name == "RightLowerLeg_BusoLayer1" or v.Name == "RightLowerLeg_BusoLayer2" or v.Name == "LeftLowerLeg_BusoLayer1" or v.Name == "LeftLowerLeg_BusoLayer2" or v.Name == "LeftFoot_BusoLayer1" or v.Name == "LeftFoot_BusoLayer2" or v.Name == "RightFoot_BusoLayer1" or v.Name == "RightFoot_BusoLayer2" then
							v.Color = Color3.fromHSV(tick() * 24 % 255/255, 1, 1)
						end
					end
				end
			end)
		end
	end
end)

Misc.newToggle("Rainbow Haki", "", false, function(value)
    RainbowHaki = value
end)

Misc.newToggle("Rainbow Yoru", "", false, function(value)
    RainbowYoru = value
end)

---- [RainbowYoru]

spawn(function()
	while wait() do
		if RainbowYoru then
			pcall(function()
				for i,v in pairs(game.Players.LocalPlayer.Character.DarkBlade.Right:GetChildren()) do
					if v.Name == "Runes" or v.Name == "Hold" or v.Name == "Bottom" or v.Name == "Gems" or v.Name == "Wings" or v.Name == "Blade" or v.Name == "Tape" then
						v.Color = Color3.fromHSV(tick() * 24 % 255/255, 1, 1)
						v.Material = "Neon"
					end

				end
			end)
		end
	end
end)

spawn(function()
	while wait(1) do
		if RainbowYoru then
			pcall(function()
				for i,v in pairs(game.Players.LocalPlayer.Character.DarkBlade.Right.Handle:GetChildren()) do
					if v.Name == "Trail" then
						v.LightEmission = 1
					end

				end
			end)
		end
	end
end)

spawn(function()
	while wait(1) do
		if RainbowYoru then
			pcall(function()
				for i,v in pairs(game.Players.LocalPlayer.Character.DarkBlade.Right.Handle.Attachment0:GetChildren()) do
					if v.Name == "Beam" then
						v.LightEmission = 1 v.Texture = 0 v.Width0 = 0 v.Width1 = 0
					end

				end
			end)
		end
	end
end)

Misc.newToggle("Auto Rejoin", "", false, function(value)
   _G.AutoRejoin = value
end)

spawn(function()
	while wait() do
		if _G.AutoRejoin then
			getgenv().rejoin = game:GetService("CoreGui").RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(child)
				if child.Name == 'ErrorPrompt' and child:FindFirstChild('MessageArea') and child.MessageArea:FindFirstChild("ErrorFrame") then
					game:GetService("TeleportService"):Teleport(game.PlaceId)
				end
			end)
		end
	end
end)


Misc.newButton("No Clip", "", function(value)
    _G.NoClip = value
end)


Misc.newButton("Remove Lave", "", function(value)
    for i,v in pairs(game.Workspace:GetDescendants()) do
		if v.Name == "Lava" then   
			v:Destroy()
		end
	end
	for i,v in pairs(game.ReplicatedStorage:GetDescendants()) do
		if v.Name == "Lava" then   
			v:Destroy()
		end
	end
end)


Misc.newToggle("Invisible (lag)", "", false, function(value)
    game.Players.LocalPlayer.Character.LowerTorso.Root:Destroy()
end)


Misc.newToggle("Invisible [Remove]", "", false, function(value)
    local removeNametags = true -- remove custom billboardgui nametags from hrp, could trigger anticheat

	local plr = game:GetService("Players").LocalPlayer
	local character = plr.Character
	local hrp = character.HumanoidRootPart
	local old = hrp.CFrame

	if not character:FindFirstChild("LowerTorso") or character.PrimaryPart ~= hrp then
		return print("unsupported")
	end

	if removeNametags then
		local tag = hrp:FindFirstChildOfClass("BillboardGui")
		if tag then tag:Destroy() end

		hrp.ChildAdded:Connect(function(item)
			if item:IsA("BillboardGui") then
				task.wait()
				item:Destroy()
			end
		end)
	end

	local newroot = character.LowerTorso.Root:Clone()
	hrp.Parent = workspace
	character.PrimaryPart = hrp
	character:MoveTo(Vector3.new(old.X,9e9,old.Z))
	hrp.Parent = character
	task.wait(0.5)
	newroot.Parent = hrp
	hrp.CFrame = old
	end) 


Misc.newButton("Max Zoom", "", function(value)
    while wait() do
		game.Players.LocalPlayer.CameraMaxZoomDistance = 9223372036854718
	end
end) 


Misc.newButton("Buddha Big", "", function(value)
    local LocalPlayer = game:GetService("Players").LocalPlayer
	local Character = LocalPlayer.Character
	local Humanoid = Character:FindFirstChildOfClass("Humanoid")

	function rm()
		for i,v in pairs(Character:GetDescendants()) do
			if v:IsA("BasePart") then
				if v.Name == "Handle" or v.Name == "Head" then
					if Character.Head:FindFirstChild("OriginalSize") then
						Character.Head.OriginalSize:Destroy()
					end
				else
					for i,cav in pairs(v:GetDescendants()) do
						if cav:IsA("Attachment") then
							if cav:FindFirstChild("OriginalPosition") then
								cav.OriginalPosition:Destroy()  
							end
						end
					end
					v:FindFirstChild("OriginalSize"):Destroy()
					if v:FindFirstChild("AvatarPartScaleType") then
						v:FindFirstChild("AvatarPartScaleType"):Destroy()
					end
				end
			end
		end
	end

	rm()
	wait(0.5)
	Humanoid:FindFirstChild("BodyProportionScale"):Destroy()
	wait(1)
end)


Misc.newButton("Kaitun Cap", "", function(value)
      local cac = require(game:GetService("Players").LocalPlayer.PlayerGui.Main.UIController.Inventory)
	local Inventory = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventory")
	local Items = {}
	local RaityLevel = {"Mythical","Legendary","Rare","Uncommon","Common"}
	local RaityColor =  {
		["Common"] = Color3.fromRGB(179, 179, 179),
		["Uncommon"] = Color3.fromRGB(92, 140, 211),
		["Rare"] =  Color3.fromRGB(140, 82, 255),
		["Legendary"] = Color3.fromRGB(213, 43, 228) ,
		["Mythical"] =  Color3.fromRGB(238, 47, 50)
	}
	function GetRaity(color)
		for k,v in pairs(RaityColor) do 
			if v==color then return k end
		end
	end

	for k,v in pairs(Inventory) do 
		Items[v.Name] = v
	end

	local total = #getupvalue(cac.UpdateRender,4)
	local rac = {}
	local allitem = {}
	local total2 = 0
	while total2<total do 
		local i = 0
		while i < 25000 and total2<total do 
			game:GetService("Players").LocalPlayer.PlayerGui.Main.InventoryContainer.Right.Content.ScrollingFrame.CanvasPosition = Vector2.new(0,i)
			for k,v in pairs(game:GetService("Players").LocalPlayer.PlayerGui.Main.InventoryContainer.Right.Content.ScrollingFrame.Frame:GetChildren()) do 
				if v:IsA("Frame") and not rac[v.ItemName.Text] and v.ItemName.Visible==true then 
					local vaihuhu = GetRaity(v.Background.BackgroundColor3)
					if vaihuhu then
						print("Rac")
						if not allitem[vaihuhu] then 
							allitem[vaihuhu] = {}
						end
						table.insert(allitem[vaihuhu],v:Clone())
					end
					total2=total2+1
					rac[v.ItemName.Text] = true
				end
			end
			i=i+20
		end
		wait()
	end
	function GetXY(vec) 
		return vec*100
	end

	local tvk = Instance.new("UIListLayout")
	tvk.FillDirection = Enum.FillDirection.Vertical
	tvk.SortOrder = 2
	tvk.Padding = UDim.new(0,10)

	local Left = Instance.new("Frame",game.Players.LocalPlayer.PlayerGui.BubbleChat)
	Left.BackgroundTransparency = 1
	Left.Size = UDim2.new(.5,0,1,0) 
	tvk.Parent = Left

	local Right = Instance.new("Frame",game.Players.LocalPlayer.PlayerGui.BubbleChat)
	Right.BackgroundTransparency = 1
	Right.Size = UDim2.new(.5,0,1,0) 
	Right.Position = UDim2.new(.6,0,0,0)
	tvk:Clone().Parent = Right
	for k,v in pairs(allitem) do 
		local cac = Instance.new("Frame",Left)
		cac.BackgroundTransparency = 1
		cac.Size = UDim2.new(1,0,0,0) 
		cac.LayoutOrder = table.find(RaityLevel,k)

		local cac2 = Instance.new("Frame",Right)
		cac2.BackgroundTransparency = 1
		cac2.Size = UDim2.new(1,0,0,0) 
		cac2.LayoutOrder = table.find(RaityLevel,k)

		local tvk = Instance.new("UIGridLayout",cac)
		tvk.CellPadding = UDim2.new(.005,0,.005,0)
		tvk.CellSize =  UDim2.new(0,70,0,70)
		tvk.FillDirectionMaxCells = 100
		tvk.FillDirection = Enum.FillDirection.Horizontal

		local ccc = tvk:Clone()
		ccc.Parent = cac2
		for k,v in pairs(v) do 
			if Items[v.ItemName.Text] and Items[v.ItemName.Text].Mastery then 
				if v.ItemLine2.Text~="Accessory" then 
					local bucac = v.ItemName:Clone()
					bucac.BackgroundTransparency = 1
					bucac.TextSize = 10
					bucac.TextXAlignment  = 2
					bucac.TextYAlignment  = 2
					bucac.ZIndex  = 5
					bucac.Text = Items[v.ItemName.Text].Mastery
					bucac.Size = UDim2.new(.5,0,.5,0)
					bucac.Position = UDim2.new(.5,0,.5,0)
					bucac.Parent = v
				end
				v.Parent = cac
			elseif v.ItemLine2.Text == "Blox Fruit" then 
				v.Parent = cac2
			end
		end
		cac.AutomaticSize = 2
		cac2.AutomaticSize = 2
	end
	local ListHuhu = {
		["Superhuman"] = Vector2.new(3,2),
		["GodHuman"] = Vector2.new(3,2),
		["DeathStep"] = Vector2.new(4,3),
		["ElectricClaw"] = Vector2.new(2,0),
		["SharkmanKarate"] = Vector2.new(0,0),
		["DragonTalon"] = Vector2.new(1,5)
	}
	local MeleeG = Instance.new("Frame",Left)
	MeleeG.BackgroundTransparency = 1
	MeleeG.Size = UDim2.new(1,0,0,0) 
	MeleeG.LayoutOrder = table.find(RaityLevel,k)
	MeleeG.AutomaticSize=2
	MeleeG.LayoutOrder = 100
	local tvk = Instance.new("UIGridLayout",MeleeG)
	tvk.CellPadding = UDim2.new(.005,0,.005,0)
	tvk.CellSize =  UDim2.new(0,70,0,70)
	tvk.FillDirectionMaxCells = 100
	tvk.FillDirection = Enum.FillDirection.Horizontal

	local cac = {"Superhuman","ElectricClaw","DragonTalon","SharkmanKarate","DeathStep","GodHuman"}
	for k,v in pairs(cac) do
		if ListHuhu[v] and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buy"..v,true) == 1 then 
			local huhu = Instance.new("ImageLabel",MeleeG)
			huhu.Image = "rbxassetid://9945562382"
			huhu.ImageRectSize = Vector2.new(100,100)
			huhu.ImageRectOffset = ListHuhu[v]*100
		end
	end
	function formatNumber(v)
		return tostring(v):reverse():gsub("%d%d%d", "%1,"):reverse():gsub("^,", "")
	end
	game:GetService("Players").LocalPlayer.PlayerGui.Main.Beli.Position = UDim2.new(0,800,0,500)
	game:GetService("Players").LocalPlayer.PlayerGui.Main.Level.Position = UDim2.new(0,800,0,550)

	local thieunang = game:GetService("Players").LocalPlayer.PlayerGui.Main.Fragments:Clone()
	thieunang.Parent = game:GetService("Players").LocalPlayer.PlayerGui.BubbleChat
	thieunang.Position = UDim2.new(0,800,0.63,0)
	local n = formatNumber(game.Players.LocalPlayer.Data.Fragments.Value)
	thieunang.Text = "Æ’"..n
	print("Done")
	pcall(function() 
		game:GetService("Players").LocalPlayer.PlayerGui.Main.MenuButton:Destroy()
	end)
	pcall(function() 
		game:GetService("Players").LocalPlayer.PlayerGui.Main.HP:Destroy()
	end)
	pcall(function() 
		game:GetService("Players").LocalPlayer.PlayerGui.Main.Energy:Destroy()
	end)
	for k,v in pairs(game:GetService("Players").LocalPlayer.PlayerGui.Main:GetChildren()) do 
		if v:IsA("ImageButton") then 
			v:Destroy()
		end
	end
	pcall(function() 
		game:GetService("Players").LocalPlayer.PlayerGui.Main.Compass:Destroy()
	end)
end)
    
Misc.newButton("Join Server", "", function(value)
    game:GetService("TeleportService"):TeleportToPlaceInstance(game.placeId, JobiJoin, game.Players.LocalPlayer)
end)

local a = game.Lighting
local c = Instance.new("ColorCorrectionEffect", a)
local e = Instance.new("ColorCorrectionEffect", a)
OldAmbient = a.Ambient
OldBrightness = a.Brightness
OldColorShift_Top = a.ColorShift_Top
OldBrightnessc = c.Brightness
OldContrastc = c.Contrast
OldTintColorc = c.TintColor
OldTintColore = e.TintColor

Misc.newToggle("RTX Mode", "", _G.RTXMode, function(value)
     _G.RTXMode = value
	if not _G.RTXMode then return end
	while _G.RTXMode do wait()
		a.Ambient = Color3.fromRGB(33, 33, 33)
		a.Brightness = 0.3
		c.Brightness = 0.176
		c.Contrast = 0.39
		c.TintColor = Color3.fromRGB(217, 145, 57)
		game.Lighting.FogEnd = 999
		if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("PointLight") then
			local a2 = Instance.new("PointLight")
			a2.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
			a2.Range = 15
			a2.Color = Color3.fromRGB(217, 145, 57)
		end
		if not _G.RTXMode then
			a.Ambient = OldAmbient
			a.Brightness = OldBrightness
			a.ColorShift_Top = OldColorShift_Top
			c.Contrast = OldContrastc
			c.Brightness = OldBrightnessc
			c.TintColor = OldTintColorc
			e.TintColor = OldTintColore
			game.Lighting.FogEnd = 2500
			game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("PointLight"):Destroy()
		end
	end
end)
    
Misc.newButton("Unlock FPS", "", function(value)
     setfpscap(100)
end)

Misc.newButton("Invisible", "", function(value)
     game:GetService("Players").LocalPlayer.Character.LowerTorso:Destroy()
end)

Misc.newButton("Click TP Tool", "", function(value)
     local plr = game:GetService("Players").LocalPlayer
	local mouse = plr:GetMouse()
	local tool = Instance.new("Tool")
	tool.RequiresHandle = false
	tool.Name = "Teleport Tool"
	tool.Activated:Connect(function()
		local root = plr.Character.HumanoidRootPart
		local pos = mouse.Hit.Position+Vector3.new(0,2.5,0)
		local offset = pos-root.Position
		root.CFrame = root.CFrame+offset
	end)
	tool.Parent = plr.Backpack
end)

Misc.newButton("Stop All Tween", "", function(value)
	TP(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
	_G.Clip = false
end)

Misc.newButton("Remove Fog", "", function(value)
     _G.RVFG_SsXz = value
end)

task.spawn(function()
	while wait(0.01) do
		pcall(function()
			if _G.RVFG_SsXz then
				if game:GetService("Lighting"):FindFirstChild("Sky") then game:GetService("Lighting").Sky:Destroy()
				end
			end
		end)
	end
end)

Misc.newToggle("Auto Click", "", false, function(value)
     _G.click = value
end)

spawn(function()
	game:GetService("RunService").RenderStepped:Connect(function()
		if _G.click then
			pcall(function()
				game:GetService'VirtualUser':CaptureController()
				game:GetService'VirtualUser':Button1Down(Vector2.new(0,1,0,1))
			end)
		end
	end)
end)

Misc.newToggle("Bypass Tp", "", false, function(value)
function ByPass(Position)game.Players.LocalPlayer.Character.Head:Destroy()game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Position wait(.5)game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Position game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")end
end) 

Misc.newToggle("Auto Farm Fast", "", false, function(value)
_G.AutoFarmFast = value
end) 
