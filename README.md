# qa_performance_simulations_dashbird_cas
 
- In "code" folder load JMeter script "dashbird-cas-cee.jmx"
- In "CSV Data Set Config", Update "Filename" to the location of the file "learners.csv" on your machine
- Thread Group Name: "Latest Script Thread Group"
- "${name} If Controller" -> "${name} cas login" -> "password" is the latest CCE Password for MBA
- "Summary Report" Update the "Filename" to save the results on your machine in the "results" folder
