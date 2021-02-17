# Java-Code-of-Writing-in-CSV-File
A Java project created in Eclipse which reads from a CSV file and then writes in another CSV file
/**
 * 
 * @author anit
 * 
 * The "CSVFileWrite.java" program is intended to provide a Random Distribution of ReleaseTime (i.e., duration of existence) of a set of real Virtual Machines (VMs). 
 * The set of VMs are randomly chosen from more than 27000 real VMs which were hosted in a real Cloud data centers, namely Nectar Cloud in January 2014. 
 *
 * Program Input - Various information of 27000+ real VMs.
 * Program Output - Random ReleaseTime distribution of a smaller set of VMs
 *
 * To do so, from CSVFileWrite.java -> main(), we simply invoke 3 functions:
 * 
 * First, the constructor of RealReleaseTimeFromCSVFile.java is invoked
 * which reads from "workload/datafiles__nectar/2014-JAN.CSV" containing various information including ReleaseTime of 27000+ VMs 
 * to create a random ReleaseTime distribution of a set of VMs, say for 1000 VMs.
 * 
 * Second, RealReleaseTimeFromCSVFile.java -> getReleaseTimeArray() is invoked from main()
 * which returns that ReleaseTime distribution
 * 
 * Finally, CSVFileWrite.java -> WriteReleaseTimeArrayInCSVFile(ArrayList<Double>) is invoked from main()
 * which writes that ReleaseTime distribution in "Output/OutputRandomlySelectedReleaseTime.CSV"
 * 
 */
Source Code can be found in 2 files - 
1. "CSVFileWrite-17022021/src/csvfilewrite/CSVFileWrite.java" - has the main()
2. "CSVFileWrite-17022021/src/readFromCSVFile//RealReleaseTimeFromCSVFile.java" - Its constructor is called from CSVFileWrite.java -> main() to create ReleaseTime Distribution

Input File: "workload/datafiles__nectar/2014-JAN.CSV" consists various information of 27000+ real VMs.
Outout File: "Output/OutputRandomlySelectedReleaseTime.CSV" provides random ReleaseTime distribution of 1000 VMs.

