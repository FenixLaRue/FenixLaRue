- 📫 Docs FLR Fazioni 12/07/2022

Config = {}

Config.TriggerBossMenu = "esx_society:openBossMenu" -- INSERIRE TRIGGER
Config.LogShop = "" -- INSERIRE WEBHOOK
Config.LogMercatoNero = "" -- INSERIRE WEBHOOK
Config.LogPuliziaSoldi = "" -- INSERIRE WEBHOOK

Config.Zones = {
    LasPlaya = { -- Nome randomico
        Pos = {
            {x = -1428.62, y = -1265.55, z = 3.65} -- coords
        },
        Lavoro = 'lasplaya', -- nome job
        LabelMenu = 'Negozio LasPlaya', -- label del menu
        Items = {
            { nome = 'vine', label = 'Vino Bianco', prezzo = 100 },
            { nome = 'portellen', label = 'Whisky', prezzo = 80 },
            { nome = 'water', label = 'Acqua', prezzo = 30 },
            { nome = 'vodka', label = 'Vodka', prezzo = 100 },
            { nome = 'pinacolada', label = 'Pina Colada', prezzo = 100 },
            { nome = 'wine', label = 'Vino Rosso', prezzo = 100 },
            { nome = 'caviale', label = 'Caviale', prezzo = 450 },
            { nome = 'ostriche', label = 'Ostriche', prezzo = 100 },
            { nome = 'fritto', label = 'Frittura Mista', prezzo = 50 },
            { nome = 'icetea', label = 'Thè Freddo', prezzo = 50 },
            { nome = 'bruschettamare', label = 'Bruschetta Mare', prezzo = 50 },
            { nome = 'sexonthebeach', label = 'Sex On The Beach', prezzo = 50 },
            { nome = 'vongole', label = 'Spaghetti allo scoglio', prezzo = 50 },
            { nome = 'champagne', label = 'Champagne', prezzo = 300 },
        }				
    },
}

Fazioni = {
     lasplaya = { -- nome job
         pesoinventario = 1200000, -- peso del primo inventario, esempio = 1200000 = 1200kg
         pesoinventario2 = 1300000, -- peso del secondo inventario, esempio = 1300000 = 1300kg
         blipvestiti = vector3(9.9, -1264.85, 3.9), -- coordinate blip vestiti
         bossmenu = vector3(-1429.46, -1272.16, 3.87), -- coordinate boos menu
         slots = 75, -- numero di slots del primo inventario
         slots2 = 100, -- numero di slots del secondo inventario
         inventario = vector3(-1426.09, -1261.98, 3.59), -- coordinate primo inventario
         inventario2 = vector3(0.0, 0.0, 0.0), -- coordinate secondo inventario
         gradoinv1 = 0, -- grado per accedere al primo inventario
         gradoinv2 = 1, -- grado per accedere al secondo inventario
         illegale = false, -- se messo su false, si puo mettere il nil per quanto riguarda le opzioni qua sotto
                           -- se messo su true, è obbligatorio fornire coordinate e valori per tutte le opzioni qua sotto
         gradoarmeria = nil, -- non inserire il nome del grado, inserire il numero
         armerianera = nil, -- coordinate
        -- armi = {
       --     {label = ('Fascette <span style="color:green;">150000$</span>'), item = 'manette', prezzo = 150000},
        --    {label = ('Sacchetto <span style="color:green;">500$</span>'), item = 'headbag', prezzo = 500},
        --    {label = ('Pistola <span style="color:green;">40000$</span>'), item = 'WEAPON_PISTOL', prezzo = 40000},
        --}
        puliziasoldi = nil, -- coordinate
        percentuale = nil, -- percentuale pulizia denaro
        gradopulizia = nil, -- non inserire il nome del grado, inserire il numero
     },
}

Personali = {
     Fenice = { -- nome randomico
         inventario = vector3(-1450.46, -1272.16, 3.87), -- coordinate inventario
         hex = "steam:11000014abef1f6", -- steam hex che deve avere accesso all'inventario
         slots = 100, , -- numero di slots del primo inventario
         pesoinventario = "600000", -- peso dell'inventario, esempio = 600000 = 600kg
     },
}

Veicoli = {
     bellevue = { -- nome job
         posizione = vector3(592.5955, -3.6381, 70.6280), -- posizione blip
         veicoli = {"veicolotest1", "veicolotest2"}, -- veicoli nel blip
         label = {"Veicolo di Prova", "Veicolo di Prova2"}, -- label di come escono i veicoli
         heading = 184.5, -- heading
         livrea = 0 -- livrea
     },
}
