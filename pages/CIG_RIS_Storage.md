# CIG RIS Storage

## Storage1

**CCDG 2**\
Path: /storage1/fs1/ccdg2\

## Storage2

**Epignome**\
Path: /storage2/fs1/epigenome

**HPRC**\
Path: /storage2/fs1/hprc

## Storage3

Reserved 110 TB for future allocation adjustments or emerging project needs. Portions may be reallocated as required to expand the spaces above.

### Permissions Groups
* Admin - Read/Write to all allocations except Wang TCGA
  * Chad, Eddie, Daaofeng
* BICAN Users
* HPRC Users
* MOHD Users
* CIG/Wang Lab Users

### Allocations

**BICAN Data**\
Path: /storage3/fs1/bican_data\
Size: 5 TB\
Perm: BICAN users (Read Only); Admin (Read/Write)\
Desc: For BICAN primary data\

**BICAN Analysis**\
Path: /storage3/fs1/bican_analysis\
Size: 5 TB\
Perm: BICAN Users & Admin (Read/Write); Others (Read Only)\
Desc: Space for user analyses, with shared and individual user paths\

**HPRC Data**\
Path: /storage3/fs1/hprc_data\
Size: 250 TB\
Perm: HPRC Users (Read Only); Admin (Read/Write)\
Desc: HPRC primary data\

**HPRC Analysis**\
Path: /storage3/fs1/hprc_analysis\
Size: 250 TB\
Perm: HPRC Users & Admin (Read/Write); Others (Read Only)\
Desc: Space for user analyses, with shared and individual user paths\

**MOHD Data**\
Path: /storage3/fs1/mohd_data\
Size: 45 TB\
Perm: Admin & Shihua (Read/Write); MOHD Users (Read Only)\
Desc: For MOHD primary data\

**MOHD Analysis**\
Path: /storage3/fs1/mohd_analysis\
Size: 15 TB\
Perm: MOHD Users & Admin (Read/Write); Others (Read Only)\
Desc: Space for user analyses, with shared and individual user paths\

**References **\
Path: /storage3/fs1/cig_references\
Size: 20 TB\
Perm: All Users (Read Only); Admin (Read/Write)\
Desc: Central repository for all linear references, assemblies, pangenome graphs, and index files and databases\

**Wang Lab TCGA**\
Path: /storage3/fs1/wang_lab_tcga\
Size: 100 TB\
Perm: Ju Heon & Authorized Users (Read/write)\
Desc: Contains compressed TCGA datasets from Ju Heon. Access restricted to Ju Heon, authorized users, and admin\
