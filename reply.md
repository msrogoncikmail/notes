Hello Michal

I got additional questions from Onectus CEO regarding your profile, could you please provide answers for the below questions? :

1. **Has he operated production Ceph clusters directly? If yes, how many clusters, what scale, and which Ceph versions?**  
   Yes, I operated Ceph clusters directly between **2020 and 2022** using **Ceph Mimic, Nautilus, and Octopus**.  
   Clusters were deployed with **ceph-ansible**, with automation triggered via **GitLab CI**.  
   I worked with approximately **25–30 clusters**.  
   Typical cluster layout was **3 MONs** and **3–12 OSD nodes**, with each OSD node usually running **6 OSDs** (e.g., `osd.0`–`osd.5`, one per disk).

2. **Has he worked with Rook-Ceph in Kubernetes in production?**  
   No — to be fully transparent, I do not have hands-on production experience with Rook-Ceph.

3. **Has he performed Ceph upgrades, OSD maintenance, cluster expansion, rebalancing, or recovery after incidents?**  
   Yes. In that environment, upgrades and configuration changes were managed through **Ansible** and executed via **pipeline triggers** (GitLab CI).  
   Ongoing maintenance, rebalancing, and incident recovery were part of my regular day-to-day responsibilities.  
   I also handled lower-level infrastructure maintenance when needed (for example, storage controller tasks using **Smart Array utilities** and similar tools).

4. **Does he have experience troubleshooting issues such as degraded PGs, slow ops, MON quorum issues, full OSDs, or backfill/recovery performance?**

5. **Has he worked with OpenStack + Ceph integration, for example Cinder / Glance / Nova with RBD?**

6. **Does he have hands-on experience with Helm, as it is also part of the required stack?**

Waiting for your information.
