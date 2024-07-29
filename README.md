# LibraryFile

```local MyUILib = loadstring(game:HttpGet("https://raw.githubusercontent.com/Eradate/LibraryFile/main/Libraryui"))()```

```local window = MyUILib:CreateWindow("My UI")```
```local tab1 = MyUILib:CreateTab(window, "Tab 1")```
```local tab2 = MyUILib:CreateTab(window, "Tab 2")```
```
MyUILib:CreateButton(tab1, "Click Me", function()
    print("Button clicked!")
end)```

```MyUILib:CreateDropdown(tab1, "Select Option", {"Option 1", "Option 2", "Option 3"}, function(selected)
    print("Selected:", selected)
end)```

```MyUILib:CreateLabel(tab1, "This is a label")```

```MyUILib:CreateButton(tab2, "Another Button", function()
    print("Another button clicked!")
end)```

```MyUILib:CreateLabel(tab2, "This is another label")```
