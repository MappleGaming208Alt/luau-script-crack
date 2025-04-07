# luau-script-crack
This can crack any luaarmour link.
```
local HttpService = game:GetService("HttpService")

-- URL of the website
local url = "https://example.com" -- Replace with your desired URL

-- Fetch website content
local success, response = pcall(function()
    return HttpService:GetAsync(url)
end)

if success then
    print("Website content:")
    print(response)
else
    print("Failed to fetch website. Error:", response)
end
```
