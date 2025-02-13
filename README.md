se game.PlaceId == 2753915549 então
    Mundo1 = verdadeiro
elseif game.PlaceId == 4442272183 então
    Mundo2 = verdadeiro
elseif game.PlaceId == 7449423635 então
    Mundo3 = verdadeiro
outro
    game:GetService("Jogadores").LocalPlayer:Kick("Não dê suporte, aguarde...")
fim

função CheckQuest()
    MeuNível = jogo:GetService("Jogadores").LocalPlayer.Data.Level.Value
    se World1 então
        se MyLevel == 1 ou MyLevel <= 9 então
            Seg = "Bandido"
            LevelQuest = 1
            NomeQuest = "BanditQuest1"
            NomeMon = "Bandido"
            CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
            CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)
        elseif MeuNível == 10 ou MeuNível <= 14 então
            Seg = "Macaco"
            LevelQuest = 1
            NomeQuest = "JungleQuest"
            NomeMon = "Macaco"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1448.51806640625, 67.85301208496094, 11.46579647064209)
        elseif MeuNível == 15 ou MeuNível <= 29 então
            Seg = "Gorila"
            LevelQuest = 2
            NomeQuest = "JungleQuest"
            NomeMon = "Gorila"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1129.8836669921875, 40.46354675292969, -525.4237060546875)
        elseif MeuNível == 30 ou MeuNível <= 39 então
            Seg = "Pirata"
            LevelQuest = 1
            NomeQuest = "BuggyQuest1"
            NomeMon = "Pirata"
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-1103.513427734375, 13.752052307128906, 3896.091064453125)
        elseif MeuNível == 40 ou MeuNível <= 59 então
            Seg = "Bruto"
            LevelQuest = 2
            NomeQuest = "BuggyQuest1"
            NomeMon = "Bruto"
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-1140.083740234375, 14.809885025024414, 4322.92138671875)
        elseif MeuNível == 60 ou MeuNível <= 74 então
            Mon = "Bandido do Deserto"
            LevelQuest = 1
            NomeQuest = "DesertQuest"
            NomeMon = "Bandido do Deserto"
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
            CFrameMon = CFrame.new(924.7998046875, 6.44867467880249, 4481.5859375)
        elseif MeuNível == 75 ou MeuNível <= 89 então
            Mon = "Oficial do Deserto"
            LevelQuest = 2
            NomeQuest = "DesertQuest"
            NomeMon = "Oficial do Deserto"
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
            CFrameMon = CFrame.new(1608.2822265625, 8.614224433898926, 4371.00732421875)
        elseif MeuNível == 90 ou MeuNível <= 99 então
            Seg = "Bandido da Neve"
            LevelQuest = 1
            NomeQuest = "Quest de Neve"
            NomeMon = "Bandido da Neve"
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
            CFrameMon = CFrame.new(1354.347900390625, 87.27277374267578, -1393.946533203125)
        elseif MeuNível == 100 ou MeuNível <= 119 então
            Seg = "Boneco de Neve"
            LevelQuest = 2
            NomeQuest = "Quest de Neve"
            NomeMon = "Boneco de Neve"
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
            CFrameMon = CFrame.new(1201.6412353515625, 144.579game.PlaceId
