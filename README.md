# vRealize-Operations-Manager-Dashboard-VMware-Update-per-CPU-Pricing-Model

**Reason:**
Update to VMwares per-CPU Pricing Model
https://www.vmware.com/company/news/updates/cpu-pricing-model-update-feb-2020.html

**Abstract:**
"While we will still be using a per-CPU approach, now, for any software offering that we license on a per-CPU basis, we will require one license for up to 32 physical cores. If a CPU has more than 32 cores, additional CPU licenses will be required."
 
**What the Dashboard shows:**
This dashboard will support you by identifying the physical core count per CPU-Socket of your ESXi hosts and displays it in the form of a Heatmap. 
 
**How to use the Heatmap:**
The Heatmap basically shows you the following:

- pCore count < 32 = Green
- pCore count > 32 = Red
 
**Screenshot** (Homelab = no 32 pCore CPU available ;-) )

