# 2020_maternal_larval_niche_construction
Dataset and R code used for statistical analysis and to generate figures

 ____   _____     _     ____   __  __  _____ 
|  _ \ | ____|   / \   |  _ \ |  \/  || ____|
| |_) ||  _|    / _ \  | | | || |\/| ||  _|  
|  _ < | |___  / ___ \ | |_| || |  | || |___ 
|_| \_\|_____|/_/   \_\|____/ |_|  |_||_____|
                                             
This data package accompanies the paper:
Dury, G. J., Moczek, A. P. and Schwab D. B. (2020), Maternal and larval niche construction interact to shape development, survival, and 
population divergence in the dung beetle Onthophagus taurus. Evolution & Development.

Contact: Guillaume J. Dury, Email: guillaume.j.dury@gmail.com, Twitter: @GJDury
                                                                                                                                                      
                                                                             (,                                                                       
                                                                           .%&&&%%#((#                                                                
                                                                        ,/#%@@@&&@,  &&/                                                              
                                                                        #%@@%%.          (%,                                                          
                                                                     /(&@@&                  /                                                        
                                                                  .*(&@&.                      ,                                                      
                                                                  %%&                                     (.(#/#/.#&. ,                               
                                                                *%@@@#                                 .&&@@@@%    @@@@@@@@&(/*  %,/,                 
                         (/,    (/@%  /(&@@#              .,,.  *@@@@@@##%     ...,.(**,..,*,.        &&@@@@@@%         &@@#%&@@&&&@(                 
                ,    *    %#%%###&&&/&@#(%%%%&#%.((((/(((((((((/((#&./*/////**/(###((###((##/(/((((((((/#/@@@@%,             (%&@&&%%(                
                  ./  &/(#&&&&&&&&@%@%&%&&&&%///*/,*****///////(*((##(&@#/(///////((((########%###########(##(((                  &#&,&%%             
                       ,(&@@&&&# .%&   (///(,***/*////////////(/(((*/###@@(//(#(/#//(##(##%#%#(####%###%###%%%/(####*                &/(%,            
                *#   #%&        ,#&.#///((((#%%######(#(((((((((/(/(#(%#%%@&%#((/(/**#(/((((((((##(####%%%%#%%%%%%%%(##*               #,/            
               #%@@&           *#&%*/(((###%#(((((((//**(**/*#**////((#%%%%@@@(((((((((((#(/#((#####%#%######%%%%%%%%%%##.              % %           
                %&&%%         /##@((((#(%#(/((//*///**********/*//(((/##%%%&@@@/#######%#######################%%###&%&#%#%               #,          
                   %&%#/(#/  *##&&/((/(#((((((//*/////*/**/*//#((/#((####%%%%%@@##%#######(###########%%%##%#%##%%#%%%%&#(%#              #           
              ,%%(%#%##(#%%#%#%@#&%%/#((((((((//(*/////////(((#(#(#####%%%%%%#@@@##%%%%%%%%%%%%%&%%%%%%%%%%%%%#%#%&%%%&&%%(#%             #           
            %%#%%(%/##(/(#####@@&&%&%#########(((/(%((#(((#(/%((#(###%%%%%%%%%&@@&%%#%%%%%%#%%#%%%%%%%%%%#%%%%%%#%%&%&&&&&%(%%           .(           
         .%&%%(##((#((/(#####@@&/(%%%##%####%#######%(#(/(#(%###%%%%%%%%%%%%%%%&@@&%&%%%#%&%%%%%&%&%%%%%#%%%%%%%%%%%%%&&&&&%%%/                       
       *%%%,((//(##((/(((###%@#*/#%%#%#%###%%#####(%######(###%%%%%%%%%%&&&%%%%&&&@&@@@%@%#(%#((##((#############%%%&%&&%%%%%&%                       
    *((&#/*(*//*/((((((#####%#(/#%#%###########(#(#(####&#%%%%&%%%%%%%%%%%%%%%%%&&@@%&#%#%%&%&%&&&&%&%%&%#&&%%%%%%%%%%#&&&&&%&%,                      
      %&%%&####((#######(####(#%#&%(%%%%####%####(#*#(%%#%#%#%%#%&%%%%%%%%%%%&%@@@@##%#&&&&@@@&&&&&@&@@&&&&&&&&&&&&&&&&@&&&&%&%,                %     
      &&&&&&&@&&&%%#%%%%%###((%&@&%&%%%%%###%(#####&#%%%%%%&&&&&&#&&&&&&&&&&&&%@@@&%&&%%%%%&%%%%%%%&&&&&&&&&&&&&&&&&&&&&&&(&%&(                 .     
       &@@&&&&&%%%%%%%%%%%%%%#&&&@&&&%%%%#%%#%%%%%%%%%%%%%&&&&&@&&&&&&&&&&%&&&@@@@@&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&%%&&&&%&&&%                  &    
     #(@@&@&&&&%%&%%%%&&%%%%%(@@&@&&&%%%%%%%%%%&&&%%&&&&&&&&&&&&&&&&@@&&&&&&&@@@@#@&&&&%%%%%%%&&&&&&&&&&&&&&&&&&&&&&&&&&&%%%&%                   &.   
         ##%&&%%%#%%&&%%&%%%%%/@@@&@@&&%%%%&%&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&@@@%@@&@&@@&@&@@@@@@&&&&&&&&&&&&&&&&&&&&&&&&##&%%                   %#   
             #/&&%%%%%%&&&&%&%%(@@@&&#%%&%%%%&&&&&&&&&&&&&&&&&&&&&&&&@@&&&&&@@@&@@@@&@&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&%&&%.                  #,&    
                %%(&&&&&%%%%, #%/ %%%%##%&&&%&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&@@@&&&&&&&&&&&&&&&&&&&&&&&@@&&&&&&&&&&&&&&&&%&%%                   @.#&    
                   .%.         (#@%&%&%##%%&&&&&&&&@@&&&&&&&&&&&&&&&&&&&&&@@@&&&&&&&&&&&&&&&&@&&&&&&&&&&&@&&&&&&&&&&&&%%&,                   @(%& .   
               #%&@%%           #/@##%%%%%%%%&&&&&&&&&&&&&&&&&&&&&&&&@&&@@@@&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&%&%                    ##&&.     
               %&&&@             #%&#%%%%%%%##%%%%%%%%%%&&&&&&&&&&&&%&&&@@&&&&&&&&&&&&&&&&&&&&&&&&&&&@&&&&&&&&&&&&&&&(                   #%&%&%       
                                  /*& %%%%%%%%%%%%%%%%%%%&&&&&&&&&&#&&@@&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&%%%@&(@@@@#              (###&%#%%.       
                                    (#%    .&%%%&#%%&%%%&&&&&&&%&&%%&%%%%%&%&&&&&&&&&&&&&&&&&&&&&&&&&&%%#%/@@@@&@@@@@@@#         .#&&%&##( .,*(,      
                     *(               .(%%%%%#((&&*(#%%%%#%#&, %(@@@@%%#&(#&%(#/#%(##%#%%##((#%&%&,          &@@@@@@@@@@.    .##@&&@@%(.              
                        %&&&&@@&@&&&&&@@@##&&&&&&&            ,/@@@@@@@@@&&&                                   ./@@@@@@@(%#&%&&%                      
                    ((&@&&%%@@&@%%@&&@%@%&&&&                  ,@@@@@@&%%.                                            ,%(                             
                  (  &   &@&&  %%@@& %&&                        &&&@&%                                                                                
                 (       ##     #%                               ,@&                                                                                  
                                                                   &&@@&  .                 &,                                                        
                                                                   * &&@&@&               %                                                           
                                                                       &&&@#@@(        (&                                                             
                                                                          &#@@@@&.*(%%*.                                                              
                                                                           %%@@&&&#. #   ,%                                                           
                                                                            &/                                                                        
                                                                                                                                                      
Included are one data file (in .csv format) and the R code for all analyses (an .Rmd file and a .Rproj file). 
All files should be in a single folder.

*************************************************************
* Data file: OnthophagusNCdata.csv
*************************************************************
Each ROW in the data files represents measurements for a single individual Onthophagus taurus dung beetle.

Column headers:
Sample.number - a unique number given to each individual at the end of the project.
Plate.number - Each individual was raised in one (or a series) of twelve-well tissue-culture plate; this lists which plate(s) the individual was reared in.
ID - This column either gives the well number in the plate, or a unique identifier.
Dung.batch - All larvae were reared on one of two batches of dung, that were each the result of a large amount of dung mixed to homogenize.
Batch - Breeding containers, used to obtain larvae, were set up as batches; these are those batches.
Pop - Population from which the beetles were taken, either Western Australia or North Carolina (Eastern United States in the paper).
NC - Larval niche construction treatment; "-" for larvae that were placed into a new artificial brood ball every 48 hours & "+" for larvae that were briefly taken out of their artificial brood ball, but then returned to it.
Temp - Maternal niche construction treatment; "Constant" for constant 25±0°C & Fluctuating for 25±6°C (cooler at night, warmer during the day, 12:12h cycle).
Date.Hatching - Date that the individual in question hatched from its egg.
Date.First.Transfer - Date that the individual was first transferred into an artificial brood ball.
Mass.3rd.Ins - Mass of third instar larvae 10 days into their 3rd (final) instar; this is usually close to the peak weight of larvae (in mg).
Date.3rd.Ins - Date that the individual reached its third larval instar.
Date.PP - Date that the individual reached the pre-pupal stage (during which larvae empty their gut in preparation for pupation).
Date.Pupa - Date that the individual reached the pupal stage.
Days.to.Pupa - Number of days that the individual took to reach the pupal stage. 
Mass.Pupa - Mass of pupae (in mg).
Day.Adult - Date at which the individual reached adulthood.
Adult.Body.Size - Width of the thorax (in mm).
Day.Dead - Date at which the individual died (if applicable).
Exclude.date.3rd - (see below).
Exclude.Mass.3rd - (see below).
Exclude.Mass.pupa - (see below, also counts as Exclude.Date.pupa).
Exclude.adult - (see below).
Exclude.death - (see below).
Exclude.all - (see below).
For all columns starting in "Excldude": 
• "Yes" means the individual was accidentally killed, and therefore the datapoint in the corresponding column for this individal should be excluded.
• "Maybe" means the individual was accidentally injured, and therefore the datapoint in the corresponding for this individal should probably be excluded, despite the survival to the injury.
• "No" means the individual was not accidentally injured or killed, therefore should not be excluded from the analysis.
For example, if an individual was killed as a pupa, the columns for 'Exclude.date.3rd', 'Exclude.Mass.3rd', and 'Exclude.Mass.pupa' would contain "No", and the columns 'Exclude.adult' and 'Exclude.death' would contain "Yes".
Notes - Notes, generally on when the individual reached second larval instar, when it was injured or how it died (if applicable), etc.

*************************************************************
* Analysis file 1: 2020_maternal_larval_niche_construction.Rproj
* Analysis file 2: 2020_maternal_larval_niche_construction.Rmd
* Log of package versions: renv.lock
*************************************************************

Main analysis file used to generate all statistical analyses and all figures.
The "2020_maternal_larval_niche_construction.Rproj" script can be run which will in turn source the .Rmd script.
After instaling all the packages necessary, running the script will recreate all the statistical analyses and recreate the base figures (which were manually formatted in Inkscape using the exported vector versions).
