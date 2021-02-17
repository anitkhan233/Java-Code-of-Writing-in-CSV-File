# Java-Code-of-Writing-in-CSV-File
A Java project created in Eclipse which reads from a CSV file and then writes in another CSV file
/**
 * 
 * @author anit
 * 
 * The "CSVFileWrite.java" program is intended to create a random distribution of duration of existence, aka ReleaseTime of 1000 VMs. 
 * ReleaseTime of 1000 VMs are randomly selected from a total of 27024 VMs which were hosted in a Cloud data centers, namely Nectar Cloud in January 2014. 
 * 
 * To do so, in main(), we simply invoke 3 functions:
 * 
 * First, the constructor of RealReleaseTimeFromCSVFile.java is invoked
 * which reads from "workload/datafiles__nectar/2014-JAN.CSV" containing various information of 27024 VMs 
 * and creates a random distribution of lifetime of 1000 VMs
 * 
 * Second, getReleaseTimeArray() of RealReleaseTimeFromCSVFile.java is invoked from main()
 * which returns that random distribution of lifetime of 1000 VMs 
 * 
 * Finally, WriteReleaseTimeArrayInCSVFile(ArrayList<Double>) is invoked from main()
 * which writes that random distribution of lifetime of 1000 VMs in "Output/OutputRandomlySelectedReleaseTime.CSV"
 * 
 */
