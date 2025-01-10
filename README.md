-- Setting the "Rc7" Executor
local Rc7 = function()
    -- The code you want to run
    local code = "print('Running Loadstring...')"
    
    -- Load and run the code
    local func = loadstring(code)
    
    -- Verifying that the function has been loaded correctly
    if func then
        func()  -- Executes the loaded code
    else
        print("Error loading code.")
    end
end

-- Running the Rc7 Executor
Rc7()
