# syscall-dataset
The dataset of "A New Federated Learning Model for Host Intrusion Detection System under Non-IID Data", named FHIDS, is collected by the eBPF data collection module for host-based intrusion detection research
# dataset organization structure    
The system call sequence dataset is collected based on Ubuntu18.04 and includes two categories: attack and normal. The normal category data is collected from the system that normally provides services, and the attack data is collected from the corresponding software vulnerability using the Metasploit penetration detection framework. The structure is as follows:

    FHIDS/
      attack/
        Cryptomining/
        FTP/
        Nginx/
        Redis/
        SSH/
      normal/
        FTP/
        Git/
        Hadoop/
        Nginx/
        Redis/
        SSH/     
