# vtriage activity, 2026-10

Built from the files in logs/. Older months are in that folder too.


#######  Stampede  #######

======================================================================
2026-10-10 05:55 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

My jobs in the queue: 0
  free slots under limit 10: 10

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  incomplete: 1
  not submitted: 99

======================================================================
2026-10-10 05:56 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
$ vtriage status
Result: checked

My jobs in the queue: 0
  free slots under limit 10: 10

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000: 1
  incomplete: 1

======================================================================
2026-10-10 09:32 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

My jobs in the queue: 0
  free slots under limit 10: 10

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  incomplete: 1
  not submitted: 99

======================================================================
2026-10-10 09:38 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

My jobs in the queue: 0
  free slots under limit 10: 10

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  incomplete: 1
  not submitted: 99

======================================================================
2026-10-10 09:43 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set --queue-limit 10
Result: finished

Jobs in queue: 0 of limit 10

Folders to submit: 10
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
Not submitted now because of the limits: 90
Type yes to save each run and submit: Submitted job 3586859: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
Submitted job 3586860: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
Submitted job 3586861: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
Submitted job 3586862: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
Submitted job 3586863: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
Submitted job 3586864: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
Submitted job 3586865: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
Submitted job 3586866: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
Submitted job 3586867: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
Submitted job 3586868: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009

Submitted: 10
Run the same command again later for the next batch.

======================================================================
2026-10-10 16:41 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

My jobs in the queue: 10
  pending: 10
  free slots under limit 10: 0

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  running or pending: 10
  not submitted: 90

======================================================================
2026-10-10 16:42 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set --queue-limit 20
Result: finished

Jobs in queue: 10 of limit 20

Folders to submit: 10
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
Not submitted now because of the limits: 80
Type yes to save each run and submit: Submitted job 3587558: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
Submitted job 3587559: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
Submitted job 3587560: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
Submitted job 3587561: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
Submitted job 3587562: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
Submitted job 3587563: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
Submitted job 3587564: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
Submitted job 3587565: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
Submitted job 3587566: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
Submitted job 3587567: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019

Submitted: 10
Run the same command again later for the next batch.


#######  perlmutter  #######

======================================================================
2026-10-09 13:12 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac
$ vtriage status
Result: checked

My jobs in the queue: 15
  pending: 15
  free slots under limit 15: 0

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac: 61
  crashed after reaching accuracy: 33
  running or pending: 15
  not submitted: 12
  missing inputs: 1

======================================================================
2026-10-09 13:21 | perlmutter | /global/u1/g/garora/vasp_triage
$ vtriage status
Result: checked

My jobs in the queue: 15
  pending: 15
  free slots under limit 15: 0

Folders under /global/u1/g/garora/vasp_triage: 0

======================================================================
2026-10-09 13:23 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac
$ vtriage status
Result: checked

My jobs in the queue: 15
  pending: 15
  free slots under limit 15: 0

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac: 61
  crashed after reaching accuracy: 33
  running or pending: 15
  not submitted: 12
  missing inputs: 1

======================================================================
2026-10-09 13:26 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/1-SQS_strs/6-6Y/1-relaxing
$ vtriage status
Result: checked

My jobs in the queue: 15
  pending: 15
  free slots under limit 15: 0

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/1-SQS_strs/6-6Y/1-relaxing: 4
  crashed after reaching accuracy: 4

======================================================================
2026-10-10 03:34 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
Result: checked

My jobs in the queue: 6
  pending: 1
  running: 5
  free slots under limit 15: 9

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 9
  running or pending: 6

Needs a look:
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0% [SCF at NELM]

======================================================================
2026-10-10 03:34 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage status
Result: checked

My jobs in the queue: 6
  pending: 1
  running: 5
  free slots under limit 15: 9

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 9
  running or pending: 6

Needs a look:
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0% [SCF at NELM]

======================================================================
2026-10-10 07:45 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

My jobs in the queue: 5
  running: 5
  free slots under limit 15: 10

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  crashed after reaching accuracy: 1
  crashed: 1

======================================================================
2026-10-10 07:46 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: checked

My jobs in the queue: 5
  running: 5
  free slots under limit 15: 10

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  crashed after reaching accuracy: 1
  crashed: 1

======================================================================
2026-10-10 07:46 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: finished

Jobs in queue: 5 of limit 15

Folders to submit: 1
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC
Submitted job 59632854: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC

Submitted: 1

======================================================================
2026-10-10 07:46 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: checked

My jobs in the queue: 6
  pending: 1
  running: 5
  free slots under limit 15: 9

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  crashed after reaching accuracy: 1
  running or pending: 1

======================================================================
2026-10-10 07:48 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage submit --group converged --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: finished

Jobs in queue: 6 of limit 15
No folders selected.

======================================================================
2026-10-10 07:48 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: checked

My jobs in the queue: 6
  pending: 1
  running: 5
  free slots under limit 15: 9

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  crashed after reaching accuracy: 1
  running or pending: 1

======================================================================
2026-10-10 07:48 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage list converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-10 07:48 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: checked

My jobs in the queue: 6
  pending: 1
  running: 5
  free slots under limit 15: 9

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  crashed after reaching accuracy: 1
  running or pending: 1

======================================================================
2026-10-10 07:48 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage submit --status crashed after reaching accuracy --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: finished

Jobs in queue: 6 of limit 15
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS

Folders to submit: 1
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS
Submitted job 59632926: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS

Submitted: 1

======================================================================
2026-10-10 07:49 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
Result: checked

My jobs in the queue: 7
  pending: 2
  running: 5
  free slots under limit 15: 8

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 10
  running or pending: 5

Needs a look:
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0% [SCF at NELM]

======================================================================
2026-10-10 08:19 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

Jobs from this folder: 2
  pending: 2

All my jobs in the queue: 5
  pending: 2
  running: 3
  free slots under limit 15: 10

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  running or pending: 2

======================================================================
2026-10-10 08:30 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

Jobs from this folder: 2
  pending: 2

All my jobs in the queue: 5
  pending: 2
  running: 3
  free slots under limit 15: 10

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  running or pending: 2

======================================================================
2026-10-10 08:33 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage status
Result: checked

Jobs from this folder: 3
  running: 3

All my jobs in the queue: 5
  pending: 2
  running: 3
  free slots under limit 15: 10

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 12
  running or pending: 3

Needs a look:
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0% [SCF at NELM]

======================================================================
2026-10-10 08:38 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage status
Result: checked

Jobs from this folder: 3
  running: 3

All my jobs in the queue: 5
  pending: 2
  running: 3
  free slots under limit 15: 10

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 12
  running or pending: 3

Needs a look:
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0% [SCF at NELM]

======================================================================
2026-10-10 14:33 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  pending: 2
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 15

Needs a look:
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1% [SCF at NELM]

======================================================================
2026-10-10 14:48 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

Jobs from this folder: 2
  running: 2

All my jobs in the queue: 2
  running: 2
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  running or pending: 2

======================================================================
2026-10-10 18:22 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

Jobs from this folder: 1
  running: 1

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  crashed after reaching accuracy: 1
  running or pending: 1

