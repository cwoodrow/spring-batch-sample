Exemple de batch de traitement de fichiers en mode séquentiel ou parallèle.

Usage : 

    mvn clean install
    
    # launch sequential version
    java -jar SpringBatchSample.jar sequential-context.xml printJob
   
    # launch parallel version
    java -jar SpringBatchSample.jar parallel-context.xml printJobParallel

