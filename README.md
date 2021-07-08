# Basic_garage
Esse codigo, tem intuito de facilitar o sistema de tranca de veículos, subistuindo a hash, pela native Gethashkey do cfx, esse codigo possui todos os veículos do gta 5 já configurados para FIVEM com essa native.

A diferença e que a hash que teria que ser copiada de cada veículo, agora apenas precisa do spawn do veículo, já que a native fara o papel de pegar a hash.
Exemplo:
 { ['name'] = "baller", ['hash'] = -808831384, ['banned'] = false },
 { ['name'] = "baller", ['hash'] = GetHashKey('baller'), ["banned"] = false },

Discord: KFS#9611

Tutorial de Uso:
Diretorio de instalação, substituir o arquivo basic_garage.lua, em VRP/CLIENT/Basic_garage.lua
