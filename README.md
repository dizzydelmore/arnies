# arnies
appliances
start
  declarations
    string model_Name
    Num line 1 = height
    num line 2 = width
    num line 3 = depth
    num cubic_inch
    string QUIT = "XXX"
    string end_job = "XXX" end_job
  input model_name
  output model_name = quit
  loop cubic inch()
    input line1
    input line2
    input line3
    cubic_inch = line1 * line2 * line3
    output cubic_inch
    return
    quit
      cubice_inch / 1728 = cubic_feet
      output cubic_feet
      output end_job
  stop
      
