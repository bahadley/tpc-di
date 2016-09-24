TPC-DI
------

# How can I generate data for a TPC-DI benchmark trial?

TPC provides a tool that will create all files and data required for a trial run.  Its only prerequisite is Java 7+.

1) Download the TPCDI_Tools zip file at [TPC- Current Specifications](http://www.tpc.org/tpc_documents_current_versions/current_specifications.asp).

2) Unzip this file.  It will create a *Tools* directory.

3) Change into the *Tools* directory.

4) Change the *PDGF* to be all lower-case (i.e., *pdgf*).

5) Run DIGen with: `$ java -jar DIGen.jar [options]`.  An output directory (-o) and a scale factory (-sf) should be provided.  The scale factor will
determine the amount of data that is generated.

6) Run `$ java -jar DIGen.jar -h` for more detail and additional options.
