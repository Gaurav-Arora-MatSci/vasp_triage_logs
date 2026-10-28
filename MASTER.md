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

======================================================================
2026-10-12 07:57 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 10: 10

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  incomplete: 20
  not submitted: 80

======================================================================
2026-10-12 07:57 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-12 08:08 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 10: 10

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  incomplete: 20
  not submitted: 80

======================================================================
2026-10-12 08:09 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage edit --group incomplete --set EDIFF=1E-05
Result: failed, exit code 1

Error: unknown group. Use one of:
  converged
  almost_converged
  not_converged
  failed
  other

======================================================================
2026-10-12 08:10 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 10: 10

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  incomplete: 20
  not submitted: 80

======================================================================
2026-10-12 08:10 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage edit --status incomplete --set EDIFF=1E-05
Result: finished


/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
  EDIFF: 1E-04 -> 1E-05

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
  EDIFF: 1E-04 -> 1E-05

Folders to change: 20
Type yes to save each run and apply the changes: Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019

======================================================================
2026-10-12 08:11 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage edit --status incomplete --set EDIFFG=-1E-02
Result: finished


/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
  EDIFFG: -1E-03 -> -1E-02

Folders to change: 20
Type yes to save each run and apply the changes: Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019

======================================================================
2026-10-12 08:11 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage edit --status not submitted --set EDIFFG=-1E-02 --set EDIFF=1E-05
Result: finished


/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

/work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099
  EDIFF: 1E-04 -> 1E-05
  EDIFFG: -1E-03 -> -1E-02

Folders to change: 80
Type yes to save each run and apply the changes: Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
Changed: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-12 08:20 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status incomplete --root /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 0 of limit 34

Folders to submit: 20
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
Type yes to save each run and submit: Submitted job 3590674: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
Submitted job 3590675: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
Submitted job 3590676: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
Submitted job 3590677: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
Submitted job 3590678: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
Submitted job 3590679: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
Submitted job 3590680: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
Submitted job 3590681: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
Submitted job 3590682: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
Submitted job 3590683: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
Submitted job 3590684: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
Submitted job 3590685: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
Submitted job 3590686: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
Submitted job 3590687: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
Submitted job 3590688: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
Submitted job 3590689: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
Submitted job 3590690: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
Submitted job 3590691: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
Submitted job 3590692: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
Submitted job 3590693: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019

Submitted: 20

======================================================================
2026-10-12 08:20 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 20 of limit 34

Folders to submit: 14
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
Not submitted now because of the limits: 66
Type yes to save each run and submit: Submitted job 3590694: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
Submitted job 3590695: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
Submitted job 3590696: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
Submitted job 3590697: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
Submitted job 3590698: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
Submitted job 3590699: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
Submitted job 3590700: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
Submitted job 3590701: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
Submitted job 3590702: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
Submitted job 3590703: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
Submitted job 3590704: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
Submitted job 3590705: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
Submitted job 3590706: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
Submitted job 3590707: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033

Submitted: 14
Run the same command again later for the next batch.

======================================================================
2026-10-12 10:13 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 34
  pending: 34

All my jobs in the queue: 34
  pending: 34
  free slots under limit 34: 0

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  running or pending: 34
  not submitted: 66

======================================================================
2026-10-12 14:14 | Stampede | /home1/11532/garora/vasp_triage_logs
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 20
  completing: 1
  running: 19
  free slots under limit 34: 14

Folders under /home1/11532/garora/vasp_triage_logs: 0

======================================================================
2026-10-12 14:14 | Stampede | /home1/11532/garora/vasp_triage_logs
$ vtriage submit --status not submitted --root /home1/11532/garora/vasp_triage_logs
Result: finished

Jobs in queue: 20 of limit 34
No folders selected.

======================================================================
2026-10-12 14:17 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 19 of limit 34

Folders to submit: 15
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
Not submitted now because of the limits: 51
Type yes to save each run and submit: Submitted job 3592190: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
Submitted job 3592191: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
Submitted job 3592192: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
Submitted job 3592193: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
Submitted job 3592195: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
Submitted job 3592196: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
Submitted job 3592197: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
Submitted job 3592198: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
Submitted job 3592199: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
Submitted job 3592200: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
Submitted job 3592201: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
Submitted job 3592202: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
Submitted job 3592203: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
Submitted job 3592204: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
Submitted job 3592205: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048

Submitted: 15
Run the same command again later for the next batch.

======================================================================
2026-10-13 10:02 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 1
  completing: 1

All my jobs in the queue: 1
  completing: 1
  free slots under limit 34: 33

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  crashed after reaching accuracy: 42
  incomplete: 5
  running or pending: 1
  not submitted: 52

======================================================================
2026-10-13 10:03 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
not submitted | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-13 10:04 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 1
  completing: 1

All my jobs in the queue: 1
  completing: 1
  free slots under limit 34: 33

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  crashed after reaching accuracy: 42
  incomplete: 5
  running or pending: 1
  not submitted: 52

======================================================================
2026-10-13 10:05 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --max 33
Result: finished

Jobs in queue: 1 of limit 34

Folders to submit: 33
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
Not submitted now because of the limits: 19
Type yes to save each run and submit: Submitted job 3595209: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
Submitted job 3595210: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
Submitted job 3595211: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
Submitted job 3595212: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
Submitted job 3595213: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
Submitted job 3595214: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
Submitted job 3595215: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
Submitted job 3595216: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
Submitted job 3595217: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
Submitted job 3595218: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
Submitted job 3595219: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
Submitted job 3595220: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
Submitted job 3595221: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
Submitted job 3595222: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
Submitted job 3595223: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
Submitted job 3595224: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
Submitted job 3595225: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
Submitted job 3595226: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
Submitted job 3595227: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
Submitted job 3595228: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
Submitted job 3595229: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
Submitted job 3595230: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
Submitted job 3595231: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
Submitted job 3595232: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
Submitted job 3595233: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
Submitted job 3595234: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
Submitted job 3595235: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
Submitted job 3595236: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
Submitted job 3595237: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
Submitted job 3595238: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
Submitted job 3595239: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
Submitted job 3595240: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
Submitted job 3595241: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080

Submitted: 33
Run the same command again later for the next batch.

======================================================================
2026-10-13 11:05 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --max 33
Result: finished

Jobs in queue: 13 of limit 34

Folders to submit: 19
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099
Type yes to save each run and submit: Submitted job 3595408: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
Submitted job 3595409: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
Submitted job 3595410: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
Submitted job 3595411: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
Submitted job 3595412: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
Submitted job 3595413: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
Submitted job 3595414: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
Submitted job 3595415: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
Submitted job 3595416: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
Submitted job 3595417: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
Submitted job 3595418: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
Submitted job 3595419: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
Submitted job 3595420: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
Submitted job 3595421: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
Submitted job 3595422: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
Submitted job 3595423: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
Submitted job 3595424: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
Submitted job 3595425: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
Submitted job 3595426: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

Submitted: 19

======================================================================
2026-10-13 11:54 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --max 33
Result: finished

Jobs in queue: 7 of limit 34
No folders selected.

======================================================================
2026-10-13 11:55 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-13 11:55 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list incomplete
Result: 7 folders

incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084

======================================================================
2026-10-13 12:00 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list running or pending
Result: 6 folders

running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-13 12:09 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-13 12:09 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list incomplete
Result: 7 folders

incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084

======================================================================
2026-10-13 14:47 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
crashed | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
    slurm-3590681.out: [2026-10-13T01:24:07.021] error: *** JOB 3590681 ON c515-122 CANCELLED AT 2026-10-13T01:24:07 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-13 14:47 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list incomplete
Result: 8 folders

incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084

======================================================================
2026-10-13 14:47 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
Result: checked

Jobs from this folder: 1
  running: 1

All my jobs in the queue: 1
  running: 1
  free slots under limit 34: 33

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  crashed after reaching accuracy: 90
  crashed: 1
  incomplete: 8
  running or pending: 1

======================================================================
2026-10-13 14:47 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list running or pending
Result: 1 folders

running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075

======================================================================
2026-10-13 14:48 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --status incomplete --root /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 1 of limit 34

Folders to submit: 8
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
Type yes to save each run and submit: Submitted job 3596557: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
Submitted job 3596558: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
Submitted job 3596559: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
Submitted job 3596560: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
Submitted job 3596561: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
Submitted job 3596562: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
Submitted job 3596563: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
Submitted job 3596564: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084

Submitted: 8

======================================================================
2026-10-13 15:18 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --max 10
Result: finished

Jobs in queue: 8 of limit 34

Folders to submit: 10
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-000
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-001
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-002
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-003
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-004
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-005
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-006
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-007
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-008
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-009
Not submitted now because of the limits: 90
Type yes to save each run and submit: Submitted job 3596710: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-000
Submitted job 3596711: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-001
Submitted job 3596712: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-002
Submitted job 3596713: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-003
Submitted job 3596714: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-004
Submitted job 3596715: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-005
Submitted job 3596716: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-006
Submitted job 3596717: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-007
Submitted job 3596718: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-008
Submitted job 3596719: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-009

Submitted: 10
Run the same command again later for the next batch.

======================================================================
2026-10-13 15:18 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 18 of limit 34

Folders to submit: 16
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-010
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-011
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-012
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-014
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-015
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-016
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-017
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-018
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-019
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-020
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-021
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-022
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-023
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-024
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
Not submitted now because of the limits: 74
Type yes to save each run and submit: Submitted job 3596722: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-010
Submitted job 3596723: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-011
Submitted job 3596724: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-012
Submitted job 3596725: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
Submitted job 3596726: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-014
Submitted job 3596727: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-015
Submitted job 3596728: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-016
Submitted job 3596729: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-017
Submitted job 3596730: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-018
Submitted job 3596731: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-019
Submitted job 3596732: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-020
Submitted job 3596733: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-021
Submitted job 3596734: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-022
Submitted job 3596735: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-023
Submitted job 3596736: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-024
Submitted job 3596737: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025

Submitted: 16
Run the same command again later for the next batch.

======================================================================
2026-10-13 15:59 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 19 of limit 34

Folders to submit: 15
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-026
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-027
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-028
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-029
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-030
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-031
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-033
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-034
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-035
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-036
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-037
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-038
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Not submitted now because of the limits: 60
Type yes to save each run and submit: Submitted job 3596973: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
Submitted job 3596974: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-026
Submitted job 3596975: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-027
Submitted job 3596976: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-028
Submitted job 3596977: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-029
Submitted job 3596978: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-030
Submitted job 3596979: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-031
Submitted job 3596980: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
Submitted job 3596981: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-033
Submitted job 3596982: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-034
Submitted job 3596983: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-035
Submitted job 3596984: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-036
Submitted job 3596985: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-037
Submitted job 3596986: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-038
Submitted job 3596987: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039

Submitted: 15
Run the same command again later for the next batch.

======================================================================
2026-10-13 16:22 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-13 16:23 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-003
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-004
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-006
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-008
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-012
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-015
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-016
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-018
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-019
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-022
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-023
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-024
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-026
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-027
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-028
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-029
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-030
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-031
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-033
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-034
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-035
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-036
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-037
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-038
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-040
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-041
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-042
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-043
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-044
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-045
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-047
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-048
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-049
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-050
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-051
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-052
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-054
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-055
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-056
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-057
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-058
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-059
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-060
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-061
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-062
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-063
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-064
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-065
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-066
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-067
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-068
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-069
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-070
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-071
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-072
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-073
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-075
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-076
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-077
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-078
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-079
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-081
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-082
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-083
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-084
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-085
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-086
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-087
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-090
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-091
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-092
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-093
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-094
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-095
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-096
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-097
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-098
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-13 17:13 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 8 of limit 34

Folders to submit: 26
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-040
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-041
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-042
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-043
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-044
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-045
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-047
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-048
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-049
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-050
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-051
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-052
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-054
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-055
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-056
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-057
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-058
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-059
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-060
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-061
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-062
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-063
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-064
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-065
Not submitted now because of the limits: 34
Type yes to save each run and submit: Submitted job 3597237: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-040
Submitted job 3597238: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-041
Submitted job 3597239: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-042
Submitted job 3597240: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-043
Submitted job 3597241: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-044
Submitted job 3597242: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-045
Submitted job 3597243: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
Submitted job 3597244: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-047
Submitted job 3597245: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-048
Submitted job 3597246: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-049
Submitted job 3597247: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-050
Submitted job 3597248: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-051
Submitted job 3597249: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-052
Submitted job 3597250: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
Submitted job 3597251: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-054
Submitted job 3597252: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-055
Submitted job 3597253: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-056
Submitted job 3597254: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-057
Submitted job 3597255: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-058
Submitted job 3597256: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-059
Submitted job 3597257: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-060
Submitted job 3597258: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-061
Submitted job 3597259: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-062
Submitted job 3597260: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-063
Submitted job 3597261: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-064
Submitted job 3597262: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-065

Submitted: 26
Run the same command again later for the next batch.

======================================================================
2026-10-13 18:56 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 14 of limit 34

Folders to submit: 20
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-066
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-067
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-068
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-069
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-070
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-071
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-072
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-073
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-075
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-076
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-077
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-078
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-079
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-081
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-082
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-083
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-084
Not submitted now because of the limits: 15
Type yes to save each run and submit: Submitted job 3597510: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
Submitted job 3597511: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-066
Submitted job 3597512: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-067
Submitted job 3597513: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-068
Submitted job 3597514: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-069
Submitted job 3597515: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-070
Submitted job 3597516: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-071
Submitted job 3597517: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-072
Submitted job 3597518: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-073
Submitted job 3597519: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
Submitted job 3597520: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-075
Submitted job 3597521: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-076
Submitted job 3597522: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-077
Submitted job 3597523: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-078
Submitted job 3597524: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-079
Submitted job 3597525: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
Submitted job 3597526: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-081
Submitted job 3597527: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-082
Submitted job 3597528: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-083
Submitted job 3597529: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-084

Submitted: 20
Run the same command again later for the next batch.

======================================================================
2026-10-13 19:48 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 24 of limit 34

Folders to submit: 10
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-085
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-086
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-087
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-090
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-091
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-092
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-093
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-094
Not submitted now because of the limits: 5
Type yes to save each run and submit: Submitted job 3597641: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-085
Submitted job 3597642: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-086
Submitted job 3597643: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-087
Submitted job 3597644: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
Submitted job 3597645: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
Submitted job 3597646: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-090
Submitted job 3597647: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-091
Submitted job 3597648: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-092
Submitted job 3597649: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-093
Submitted job 3597650: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-094

Submitted: 10
Run the same command again later for the next batch.

======================================================================
2026-10-13 20:02 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 34 of limit 34
Queue is full. Nothing submitted.

======================================================================
2026-10-14 08:32 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
crashed | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
    slurm-3590681.out: [2026-10-13T01:24:07.021] error: *** JOB 3590681 ON c515-122 CANCELLED AT 2026-10-13T01:24:07 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
crashed | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
    slurm-3595236.out: [2026-10-13T22:45:16.017] error: *** JOB 3595236 ON c513-043 CANCELLED AT 2026-10-13T22:45:16 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-14 08:32 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list SCF not converged ionic not converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-14 08:56 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-14 09:00 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-14 09:00 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list SCF not converged ionic not converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-14 09:02 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list running or pending not submitted missing inputs
Result: 0 folders

No folder has that status.

======================================================================
2026-10-14 09:02 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list crashed incomplete
Result: 2 folders

crashed | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
    slurm-3590681.out: [2026-10-13T01:24:07.021] error: *** JOB 3590681 ON c515-122 CANCELLED AT 2026-10-13T01:24:07 DUE TO TIME LIMIT ***
crashed | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
    slurm-3595236.out: [2026-10-13T22:45:16.017] error: *** JOB 3595236 ON c513-043 CANCELLED AT 2026-10-13T22:45:16 DUE TO TIME LIMIT ***

======================================================================
2026-10-14 09:03 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list SCF not converged ionic not converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-14 09:03 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list crashed after reaching accuracy
Result: 98 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-14 09:03 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage submit --group failed --root /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 0 of limit 34

Folders to submit: 2
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
Submitted job 3599048: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
Submitted job 3599049: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075

Submitted: 2

======================================================================
2026-10-14 09:04 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-006
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-008
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-015
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-024
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-031
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-033
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-038
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-040
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-045
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-052
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
    slurm-3597250.out: [2026-10-14T06:03:39.021] error: *** JOB 3597250 ON c518-092 CANCELLED AT 2026-10-14T06:03:39 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-058
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-073
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-075
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-079
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
    slurm-3597525.out: [2026-10-14T08:39:50.197] error: *** JOB 3597525 ON c512-081 CANCELLED AT 2026-10-14T08:39:50 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-083
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-087
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-094
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-095
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-096
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-097
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-098
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-14 09:05 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status incomplete --root /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 2 of limit 34

Folders to submit: 6
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
Type yes to save each run and submit: Archived as run 1: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
Submitted job 3599052: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
Archived as run 1: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
Submitted job 3599053: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
Archived as run 1: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Submitted job 3599054: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Archived as run 1: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
Submitted job 3599055: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
Archived as run 1: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
Submitted job 3599056: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
Archived as run 1: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
Submitted job 3599057: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089

Submitted: 6

======================================================================
2026-10-14 09:05 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list incomplete
Result: 0 folders

No folder has that status.

======================================================================
2026-10-14 09:06 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-006
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-008
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-015
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-024
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-031
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-033
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-038
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-040
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-045
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-052
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
    slurm-3597250.out: [2026-10-14T06:03:39.021] error: *** JOB 3597250 ON c518-092 CANCELLED AT 2026-10-14T06:03:39 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-058
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-073
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-075
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-079
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
    slurm-3597525.out: [2026-10-14T08:39:50.197] error: *** JOB 3597525 ON c512-081 CANCELLED AT 2026-10-14T08:39:50 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-083
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-087
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-094
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-095
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-096
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-097
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-098
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-14 09:07 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list crashed
Result: 2 folders

crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
    slurm-3597250.out: [2026-10-14T06:03:39.021] error: *** JOB 3597250 ON c518-092 CANCELLED AT 2026-10-14T06:03:39 DUE TO TIME LIMIT ***
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
    slurm-3597525.out: [2026-10-14T08:39:50.197] error: *** JOB 3597525 ON c512-081 CANCELLED AT 2026-10-14T08:39:50 DUE TO TIME LIMIT ***

======================================================================
2026-10-14 09:07 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list missing inputs
Result: 0 folders

No folder has that status.

======================================================================
2026-10-14 09:07 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list not submitted
Result: 6 folders

not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-095
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-096
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-097
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-098
not submitted | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-14 09:08 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 8 of limit 34

Folders to submit: 6
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-095
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-096
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-097
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-098
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-099
Type yes to save each run and submit: Submitted job 3599064: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
Submitted job 3599065: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-095
Submitted job 3599066: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-096
Submitted job 3599067: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-097
Submitted job 3599068: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-098
Submitted job 3599069: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-099

Submitted: 6

======================================================================
2026-10-15 13:07 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 34: 34

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  crashed after reaching accuracy: 100

======================================================================
2026-10-15 13:07 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-15 13:07 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage list crashed after reaching accuracy
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-15 13:08 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage report /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
Result: finished

Directories: 100
Files written:
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/report_15_Oct_26_1_08PM/report_all.csv
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/report_15_Oct_26_1_08PM/report_converged.csv
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/report_15_Oct_26_1_08PM/report_almost_converged.csv
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/report_15_Oct_26_1_08PM/report_not_converged.csv
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/report_15_Oct_26_1_08PM/report_failed.csv
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/report_15_Oct_26_1_08PM/report_other.csv
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/report_15_Oct_26_1_08PM/report.md

======================================================================
2026-10-15 13:09 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage history /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
Result: finished

Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-000
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-001
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-002
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-003
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-004
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-005
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-006
Archived as run 3: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-007
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-008
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-009
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-010
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-011
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-012
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-013
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-014
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-015
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-016
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-017
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-018
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-019
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-020
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-021
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-022
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-023
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-024
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-025
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-026
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-027
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-028
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-029
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-030
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-031
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-032
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-033
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-034
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-035
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-036
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-037
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-038
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-039
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-040
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-041
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-042
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-043
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-044
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-045
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-046
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-047
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-048
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-049
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-050
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-051
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-052
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-053
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-054
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-055
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-056
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-057
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-058
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-059
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-060
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-061
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-062
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-063
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-064
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-065
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-066
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-067
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-068
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-069
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-070
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-071
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-072
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-073
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-074
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-075
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-076
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-077
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-078
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-079
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-080
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-081
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-082
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-083
Archived as run 2: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-084
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-085
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-086
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-087
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-088
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-089
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-090
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-091
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-092
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-093
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-094
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-095
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-096
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-097
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-098
Archived as run 1: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set/str-099

Summary:
  archived: 100

======================================================================
2026-10-15 13:12 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-006
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-008
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-015
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-024
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-033
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-038
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-040
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-052
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
    slurm-3597250.out: [2026-10-14T06:03:39.021] error: *** JOB 3597250 ON c518-092 CANCELLED AT 2026-10-14T06:03:39 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-058
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-073
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-075
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-079
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
    slurm-3597525.out: [2026-10-14T08:39:50.197] error: *** JOB 3597525 ON c512-081 CANCELLED AT 2026-10-14T08:39:50 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-083
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-087
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-094
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-095
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-096
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-097
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-098
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-15 13:12 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list crashed incomplete
Result: 4 folders

incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
    slurm-3597250.out: [2026-10-14T06:03:39.021] error: *** JOB 3597250 ON c518-092 CANCELLED AT 2026-10-14T06:03:39 DUE TO TIME LIMIT ***
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
    slurm-3597525.out: [2026-10-14T08:39:50.197] error: *** JOB 3597525 ON c512-081 CANCELLED AT 2026-10-14T08:39:50 DUE TO TIME LIMIT ***

======================================================================
2026-10-15 13:13 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status incomplete --root /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 0 of limit 34

Folders to submit: 2
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Type yes to save each run and submit: Archived as run 2: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
Submitted job 3603052: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
Archived as run 2: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Submitted job 3603053: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039

Submitted: 2

======================================================================
2026-10-15 13:13 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list crashed incomplete
Result: 2 folders

crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
    slurm-3597250.out: [2026-10-14T06:03:39.021] error: *** JOB 3597250 ON c518-092 CANCELLED AT 2026-10-14T06:03:39 DUE TO TIME LIMIT ***
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
    slurm-3597525.out: [2026-10-14T08:39:50.197] error: *** JOB 3597525 ON c512-081 CANCELLED AT 2026-10-14T08:39:50 DUE TO TIME LIMIT ***

======================================================================
2026-10-15 13:13 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --group failed --root /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 2 of limit 34
CONTCAR missing or empty, skipped: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053

Folders to submit: 1
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
Submitted job 3603055: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080

Submitted: 1

======================================================================
2026-10-15 13:15 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status crashed --root /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set --path=053
Result: finished

Jobs in queue: 3 of limit 34
No selected folder matches: 053
Path filter kept 0 of 1 folders.
No folders selected.

======================================================================
2026-10-16 17:21 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training --queue-limit 20
Result: finished

Jobs in queue: 1 of limit 20

Folders to submit: 19
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-018
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-019
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-020
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-021
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-022
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-023
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-024
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-027
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-028
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-029
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-030
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-032
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-033
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-034
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-035
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036
Not submitted now because of the limits: 13
Type yes to save each run and submit: Submitted job 3606857: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-018
Submitted job 3606858: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-019
Submitted job 3606859: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-020
Submitted job 3606860: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-021
Submitted job 3606861: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-022
Submitted job 3606862: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-023
Submitted job 3606863: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-024
Submitted job 3606864: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025
Submitted job 3606865: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026
Submitted job 3606866: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-027
Submitted job 3606867: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-028
Submitted job 3606868: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-029
Submitted job 3606869: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-030
Submitted job 3606870: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
Submitted job 3606871: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-032
Submitted job 3606872: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-033
Submitted job 3606873: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-034
Submitted job 3606874: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-035
Submitted job 3606875: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036

Submitted: 19
Run the same command again later for the next batch.

======================================================================
2026-10-16 20:36 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training --queue-limit 30
Result: finished

Jobs in queue: 20 of limit 30

Folders to submit: 10
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-037
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-038
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-039
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-040
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-041
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-042
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-043
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-044
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-046
Not submitted now because of the limits: 3
Type yes to save each run and submit: Submitted job 3607273: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-037
Submitted job 3607274: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-038
Submitted job 3607275: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-039
Submitted job 3607276: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-040
Submitted job 3607277: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-041
Submitted job 3607278: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-042
Submitted job 3607279: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-043
Submitted job 3607280: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-044
Submitted job 3607281: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045
Submitted job 3607282: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-046

Submitted: 10
Run the same command again later for the next batch.

======================================================================
2026-10-17 04:53 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: finished

Jobs in queue: 11 of limit 34

Folders to submit: 3
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-047
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-048
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-049
Type yes to save each run and submit: Submitted job 3607833: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-047
Submitted job 3607834: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-048
Submitted job 3607835: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-049

Submitted: 3

======================================================================
2026-10-17 04:53 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: checked

Jobs from this folder: 14
  pending: 13
  running: 1

All my jobs in the queue: 14
  pending: 13
  running: 1
  free slots under limit 34: 20

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 28
  ionic not converged: 3
  crashed: 5
  running or pending: 14

Needs a look:
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025 [SCF at NELM]

======================================================================
2026-10-17 04:56 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status
Result: checked

Jobs from this folder: 14
  pending: 13
  running: 1

All my jobs in the queue: 14
  pending: 13
  running: 1
  free slots under limit 34: 20

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 28
  ionic not converged: 3
  crashed: 5
  running or pending: 14

Needs a look:
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025 [SCF at NELM]

======================================================================
2026-10-17 04:56 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list converged
Result: 28 folders

converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-000 | -1708.39491847 eV
    slurm-59808927.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     58
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-003 | -1709.13253273 eV
    slurm-59808955.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     34
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-004 | -1714.68851728 eV
    slurm-59808962.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-005 | -1717.20083513 eV
    slurm-59808963.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     50
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-007 | -1708.55168419 eV
    slurm-59808965.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     32
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-008 | -1704.55455042 eV
    slurm-59808966.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     35
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-009 | -1709.98959376 eV
    slurm-59808967.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-011 | -1708.96493868 eV
    slurm-59808969.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     42
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-012 | -1709.66145664 eV
    slurm-59808970.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     52
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-013 | -1708.46253298 eV
    slurm-59808971.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     36
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-014 | -1705.83494126 eV
    slurm-59852428.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     25
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-015 | -1704.06225855 eV
    slurm-59852433.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     15
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-017 | -1708.07253746 eV
    slurm-59852439.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     25
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-018 | -1714.32038232 eV
    slurm-3606857.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     18
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-019 | -1707.82251126 eV
    slurm-3606858.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     28
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-020 | -1703.6065572 eV
    slurm-3606859.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     35
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-021 | -1704.11681592 eV
    slurm-3606860.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     24
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-022 | -1708.66928734 eV
    slurm-3606861.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     37
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-023 | -1710.81056446 eV
    slurm-3606862.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-024 | -1711.29957235 eV
    slurm-3606863.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     17
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-027 | -1713.26102327 eV
    slurm-3606866.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     22
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-028 | -1712.22828585 eV
    slurm-3606867.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     42
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-029 | -1709.63739725 eV
    slurm-3606868.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-030 | -1709.82041787 eV
    slurm-3606869.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     28
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-032 | -1706.30225402 eV
    slurm-3606871.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     32
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-033 | -1709.48768838 eV
    slurm-3606872.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     31
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-034 | -1709.26609787 eV
    slurm-3606873.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     19
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-035 | -1710.09393135 eV
    slurm-3606874.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     29

======================================================================
2026-10-17 04:58 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training --path=000
Result: finished

Jobs in queue: 14 of limit 34
No selected folder matches: 000
Path filter kept 0 of 50 folders.
No folders selected.

======================================================================
2026-10-17 04:58 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training --queue-limit 32
Result: finished

Jobs in queue: 14 of limit 32

Folders to submit: 18
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-000
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-001
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-002
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-003
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-004
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-006
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-007
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-008
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-009
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-010
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-011
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-012
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-013
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-014
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-015
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-016
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-017
Not submitted now because of the limits: 32
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-17 04:59 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage submit --status not submitted --root /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training --path=000
Result: finished

Jobs in queue: 14 of limit 34
No selected folder matches: 000
Path filter kept 0 of 50 folders.
No folders selected.

======================================================================
2026-10-17 06:23 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 1 of limit 34

Folders to submit: 13
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-037
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-038
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-039
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-040
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-041
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-042
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-043
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-044
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-046
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-047
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-048
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-049
Type yes to save each run and submit: Submitted job 3607893: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-037
Submitted job 3607894: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-038
Submitted job 3607895: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-039
Submitted job 3607896: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-040
Submitted job 3607897: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-041
Submitted job 3607898: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-042
Submitted job 3607899: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-043
Submitted job 3607900: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-044
Submitted job 3607901: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045
Submitted job 3607902: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-046
Submitted job 3607903: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-047
Submitted job 3607904: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-048
Submitted job 3607905: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-049

Submitted: 13

======================================================================
2026-10-17 08:59 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 15
  pending: 14
  running: 1
  free slots under limit 34: 19

Folders under /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set: 100
  crashed after reaching accuracy: 97
  crashed: 2
  incomplete: 1

======================================================================
2026-10-17 08:59 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list incomplete
Result: 1 folders

incomplete | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039

======================================================================
2026-10-17 09:00 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status incomplete
Result: finished

Jobs in queue: 15 of limit 34

Folders to submit: 1
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Type yes to save each run and submit: Archived as run 3: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Submitted job 3608191: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039

Submitted: 1

======================================================================
2026-10-17 10:28 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 1
  pending: 1

All my jobs in the queue: 16
  pending: 15
  running: 1
  free slots under limit 34: 18

Folders under /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set: 100
  crashed after reaching accuracy: 97
  crashed: 2
  running or pending: 1

======================================================================
2026-10-17 10:28 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list running or pending
Result: 1 folders

running or pending | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039

======================================================================
2026-10-17 10:29 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 16
  pending: 15
  running: 1
  free slots under limit 34: 18

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/DFT_training_set: 100
  crashed after reaching accuracy: 100

======================================================================
2026-10-17 14:02 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage status
Result: checked

Jobs from this folder: 1
  pending: 1

All my jobs in the queue: 4
  pending: 1
  running: 3
  free slots under limit 34: 30

Folders under /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set: 100
  crashed after reaching accuracy: 97
  crashed: 2
  running or pending: 1

======================================================================
2026-10-17 14:03 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status
Result: checked

Jobs from this folder: 2
  running: 2

All my jobs in the queue: 4
  pending: 1
  running: 3
  free slots under limit 34: 30

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 39
  ionic not converged: 4
  crashed: 5
  running or pending: 2

Needs a look:
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025 [SCF at NELM]

======================================================================
2026-10-17 14:05 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status crashed
Result: finished

Jobs in queue: 4 of limit 34
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001
Warning: ZBRENT: fatal error in bracketing, max force 0.8881 eV/A, max stress 75.37 kB (limit 1.0 kB), last ionic dE 5.13e-01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002
Warning: ZBRENT: fatal error in bracketing, max force 1.3629 eV/A, max stress 70.30 kB (limit 1.0 kB), last ionic dE 6.92e+01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002
Warning: ZBRENT: fatal error in bracketing, max force 0.0724 eV/A, max stress 0.06 kB (limit 1.0 kB), last ionic dE 1.20e-03 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025
Warning: ZBRENT: fatal error in bracketing, max force 0.8980 eV/A, max stress 102.85 kB (limit 1.0 kB), last ionic dE 6.86e+01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025

Folders to submit: 5
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-016
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001
Submitted job 3608657: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002
Submitted job 3608658: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006
Submitted job 3608659: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-016
Submitted job 3608660: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-016
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025
Submitted job 3608661: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025

Submitted: 5

======================================================================
2026-10-18 07:30 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 1
  running: 1
  free slots under limit 34: 33

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 43
  ionic not converged: 5
  crashed: 2

======================================================================
2026-10-18 07:30 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 1
  running: 1
  free slots under limit 34: 33

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 43
  ionic not converged: 5
  crashed: 2

======================================================================
2026-10-18 07:30 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list ionic not converged
Result: 5 folders

ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002 | -1702.29500929 eV
    slurm-59808932.out: ZBRENT: fatal error in bracketing
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010 | -1705.59888678 eV
    slurm-59808968.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     53
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031 | -1706.25031686 eV
    slurm-3606870.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     28
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036 | -1709.77611006 eV
    slurm-3606875.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     42
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045 | -1706.24582197 eV
    slurm-3607901.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     27

======================================================================
2026-10-18 07:31 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list ionic not converged
Result: 5 folders

ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002 | -1702.29500929 eV
    slurm-59808932.out: ZBRENT: fatal error in bracketing
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010 | -1705.59888678 eV
    slurm-59808968.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     53
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031 | -1706.25031686 eV
    slurm-3606870.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     28
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036 | -1709.77611006 eV
    slurm-3606875.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     42
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045 | -1706.24582197 eV
    slurm-3607901.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     27

======================================================================
2026-10-18 07:31 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status ionic not converged --root /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: finished

Jobs in queue: 1 of limit 34

Folders to submit: 5
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045  (CONTCAR to POSCAR)
Type yes to save each run and submit: CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002
Submitted job 3610738: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
Submitted job 3610739: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
Submitted job 3610740: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036
Submitted job 3610741: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045
Submitted job 3610742: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045

Submitted: 5

======================================================================
2026-10-18 07:31 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list crashed
Result: 2 folders

crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006
    slurm-59808964.out: ZBRENT: fatal error in bracketing
    max force 0.0393 eV/A, max stress 0.74 kB (limit 1.0 kB), last ionic dE 4.00e-04 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026
    slurm-3606865.out: [2026-10-17T15:56:00.049] error: *** JOB 3606865 ON c517-111 CANCELLED AT 2026-10-17T15:56:00 DUE TO TIME LIMIT ***

======================================================================
2026-10-18 07:31 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: checked

Jobs from this folder: 5
  running: 5

All my jobs in the queue: 6
  running: 6
  free slots under limit 34: 28

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 43
  crashed: 2
  running or pending: 5

======================================================================
2026-10-18 07:31 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list crashed
Result: 2 folders

crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006
    slurm-59808964.out: ZBRENT: fatal error in bracketing
    max force 0.0393 eV/A, max stress 0.74 kB (limit 1.0 kB), last ionic dE 4.00e-04 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026
    slurm-3606865.out: [2026-10-17T15:56:00.049] error: *** JOB 3606865 ON c517-111 CANCELLED AT 2026-10-17T15:56:00 DUE TO TIME LIMIT ***

======================================================================
2026-10-18 07:32 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status crashed --root /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: finished

Jobs in queue: 6 of limit 34
Warning: ZBRENT: fatal error in bracketing, max force 0.0393 eV/A, max stress 0.74 kB (limit 1.0 kB), last ionic dE 4.00e-04 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006

Folders to submit: 2
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026  (CONTCAR to POSCAR)
Type yes to save each run and submit: CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006
Submitted job 3610743: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026
Submitted job 3610744: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026

Submitted: 2

======================================================================
2026-10-18 07:32 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 100 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-000
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-001
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-002
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-003
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-004
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-005
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-006
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-007
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-008
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-009
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-010
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-011
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-012
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-013
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-014
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-015
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-016
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-017
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-018
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-019
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-020
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-021
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-022
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-023
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-024
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
    slurm-3603052.out: [2026-10-17T00:54:42.073] error: *** JOB 3603052 ON c511-092 CANCELLED AT 2026-10-17T00:54:42 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-026
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-027
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-028
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-029
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-030
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-031
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-032
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-033
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-034
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-035
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-036
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-037
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-038
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
    slurm-3608191.out: [2026-10-17T17:17:31.836] error: *** JOB 3608191 ON c514-013 CANCELLED AT 2026-10-17T17:17:31 DUE to SIGNAL Terminated ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-040
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-041
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-042
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-043
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-044
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-045
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-046
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-047
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-048
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-049
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-050
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-051
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-052
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
    slurm-3597250.out: [2026-10-14T06:03:39.021] error: *** JOB 3597250 ON c518-092 CANCELLED AT 2026-10-14T06:03:39 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-054
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-055
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-056
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-057
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-058
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-059
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-060
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-061
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-062
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-063
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-064
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-065
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-066
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-067
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-068
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-069
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-070
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-071
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-072
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-073
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-074
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-075
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-076
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-077
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-078
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-079
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-080
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-081
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-082
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-083
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-084
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-085
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-086
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-087
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-088
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-089
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-090
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-091
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-092
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-093
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-094
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-095
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-096
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-097
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-098
crashed after reaching accuracy | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-099

======================================================================
2026-10-18 07:32 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage list crashed
Result: 3 folders

crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
    slurm-3603052.out: [2026-10-17T00:54:42.073] error: *** JOB 3603052 ON c511-092 CANCELLED AT 2026-10-17T00:54:42 DUE TO TIME LIMIT ***
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
    slurm-3608191.out: [2026-10-17T17:17:31.836] error: *** JOB 3608191 ON c514-013 CANCELLED AT 2026-10-17T17:17:31 DUE to SIGNAL Terminated ***
crashed | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053
    slurm-3597250.out: [2026-10-14T06:03:39.021] error: *** JOB 3597250 ON c518-092 CANCELLED AT 2026-10-14T06:03:39 DUE TO TIME LIMIT ***

======================================================================
2026-10-18 07:33 | Stampede | /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
$ vtriage submit --status crashed --root /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set
Result: finished

Jobs in queue: 8 of limit 34
CONTCAR missing or empty, skipped: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-053

Folders to submit: 2
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Type yes to save each run and submit: Archived as run 3: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
Submitted job 3610751: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-025
Archived as run 4: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039
Submitted job 3610752: /work2/11532/garora/mecx/5-MECx_W10_6x6x6/DFT_training_set/str-039

Submitted: 2

======================================================================
2026-10-18 08:41 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  running: 2
  free slots under limit 34: 32

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 48
  crashed: 2

======================================================================
2026-10-18 08:41 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list crashed
Result: 2 folders

crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
    slurm-59808968.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     53
crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
    slurm-3610740.out: ZBRENT: fatal error in bracketing
    max force 0.0120 eV/A, max stress 0.11 kB (limit 1.0 kB), last ionic dE 4.00e-04 eV, force limit 0.01 eV/A: criteria not met

======================================================================
2026-10-18 08:41 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status crashed --root /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: finished

Jobs in queue: 2 of limit 34
Warning: ZBRENT: fatal error in bracketing, max force 0.0120 eV/A, max stress 0.11 kB (limit 1.0 kB), last ionic dE 4.00e-04 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031

Folders to submit: 2
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031  (CONTCAR to POSCAR)
Type yes to save each run and submit: Submitted job 3610894: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
Archived as run 2: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
Submitted job 3610895: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031

Submitted: 2

======================================================================
2026-10-19 06:29 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage submit --status not_submitted
Result: failed, exit code 1

Error: unknown status. Use one of:
  converged
  crashed after reaching accuracy
  SCF not converged
  ionic not converged
  crashed
  incomplete
  running or pending
  not submitted
  missing inputs

======================================================================
2026-10-19 06:29 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 0 of limit 34

Folders to submit: 34
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-000
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-001
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-002
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-003
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-004
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-006
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-007
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-008
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-009
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-010
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-011
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-012
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-013
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-014
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-015
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-016
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-017
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-018
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-020
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-021
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-022
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-023
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-025
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-026
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-027
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-028
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-029
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-030
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-032
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-033
Not submitted now because of the limits: 16
Type yes to save each run and submit: Submitted job 3614661: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-000
Submitted job 3614662: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-001
Submitted job 3614663: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-002
Submitted job 3614664: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-003
Submitted job 3614665: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-004
Submitted job 3614666: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
Submitted job 3614667: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-006
Submitted job 3614668: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-007
Submitted job 3614669: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-008
Submitted job 3614670: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-009
Submitted job 3614671: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-010
Submitted job 3614672: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-011
Submitted job 3614673: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-012
Submitted job 3614674: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-013
Submitted job 3614675: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-014
Submitted job 3614676: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-015
Submitted job 3614677: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-016
Submitted job 3614678: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-017
Submitted job 3614679: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-018
Submitted job 3614680: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019
Submitted job 3614681: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-020
Submitted job 3614682: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-021
Submitted job 3614683: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-022
Submitted job 3614684: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-023
Submitted job 3614685: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024
Submitted job 3614686: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-025
Submitted job 3614687: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-026
Submitted job 3614688: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-027
Submitted job 3614689: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-028
Submitted job 3614690: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-029
Submitted job 3614691: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-030
Submitted job 3614692: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031
Submitted job 3614693: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-032
Submitted job 3614694: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-033

Submitted: 34
Run the same command again later for the next batch.

======================================================================
2026-10-19 06:57 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 16 of limit 34

Folders to submit: 16
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-035
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-036
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-037
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-038
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-039
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-040
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-041
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-042
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-044
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-045
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-046
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-048
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-049
Type yes to save each run and submit: Submitted job 3614737: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034
Submitted job 3614738: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-035
Submitted job 3614739: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-036
Submitted job 3614740: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-037
Submitted job 3614741: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-038
Submitted job 3614742: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-039
Submitted job 3614743: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-040
Submitted job 3614744: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-041
Submitted job 3614745: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-042
Submitted job 3614746: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043
Submitted job 3614747: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-044
Submitted job 3614748: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-045
Submitted job 3614749: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-046
Submitted job 3614750: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047
Submitted job 3614751: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-048
Submitted job 3614752: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-049

Submitted: 16

======================================================================
2026-10-19 10:10 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 50 folders

converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-000 | -1708.39491847 eV
    slurm-59808927.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     58
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001 | -1711.61521207 eV
    slurm-59808930.out: ZBRENT: fatal error in bracketing
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002 | -1702.08029896 eV
    slurm-59808932.out: ZBRENT: fatal error in bracketing
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-003 | -1709.13253273 eV
    slurm-59808955.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     34
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-004 | -1714.68851728 eV
    slurm-59808962.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-005 | -1717.20083513 eV
    slurm-59808963.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     50
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006 | -1702.76987321 eV
    slurm-59808964.out: ZBRENT: fatal error in bracketing
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-007 | -1708.55168419 eV
    slurm-59808965.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     32
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-008 | -1704.55455042 eV
    slurm-59808966.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     35
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-009 | -1709.98959376 eV
    slurm-59808967.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
    slurm-59808968.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     53
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-011 | -1708.96493868 eV
    slurm-59808969.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     42
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-012 | -1709.66145664 eV
    slurm-59808970.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     52
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-013 | -1708.46253298 eV
    slurm-59808971.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     36
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-014 | -1705.83494126 eV
    slurm-59852428.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     25
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-015 | -1704.06225855 eV
    slurm-59852433.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     15
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-016 | -1704.29592618 eV
    slurm-59852436.out: [2026-10-16T21:48:34.693] error: *** STEP 59852436.0 ON nid006602 CANCELLED AT 2026-10-16T21:48:34 DUE TO TASK FAILURE ***
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-017 | -1708.07253746 eV
    slurm-59852439.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     25
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-018 | -1714.32038232 eV
    slurm-3606857.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     18
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-019 | -1707.82251126 eV
    slurm-3606858.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     28
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-020 | -1703.6065572 eV
    slurm-3606859.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     35
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-021 | -1704.11681592 eV
    slurm-3606860.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     24
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-022 | -1708.66928734 eV
    slurm-3606861.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     37
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-023 | -1710.81056446 eV
    slurm-3606862.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-024 | -1711.29957235 eV
    slurm-3606863.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     17
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025 | -1704.34732305 eV
    slurm-3608661.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     31
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026 | -1708.13004379 eV
    slurm-3610744.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     34
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-027 | -1713.26102327 eV
    slurm-3606866.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     22
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-028 | -1712.22828585 eV
    slurm-3606867.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     42
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-029 | -1709.63739725 eV
    slurm-3606868.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-030 | -1709.82041787 eV
    slurm-3606869.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     28
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031 | -1706.3432091 eV
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-032 | -1706.30225402 eV
    slurm-3606871.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     32
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-033 | -1709.48768838 eV
    slurm-3606872.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     31
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-034 | -1709.26609787 eV
    slurm-3606873.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     19
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-035 | -1710.09393135 eV
    slurm-3606874.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     29
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036 | -1709.93823455 eV
    slurm-3610741.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     17
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-037 | -1704.50150404 eV
    slurm-3607893.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     32
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-038 | -1707.47176164 eV
    slurm-3607894.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     41
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-039 | -1712.29407631 eV
    slurm-3607895.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     29
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-040 | -1705.62514348 eV
    slurm-3607896.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-041 | -1711.17453534 eV
    slurm-3607897.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     38
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-042 | -1715.76265433 eV
    slurm-3607898.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     35
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-043 | -1712.7202947 eV
    slurm-3607899.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     28
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-044 | -1715.33804615 eV
    slurm-3607900.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     30
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045 | -1706.48243531 eV
    slurm-3610742.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-046 | -1715.58754637 eV
    slurm-3607902.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     41
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-047 | -1710.22157874 eV
    slurm-3607903.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     39
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-048 | -1710.80572373 eV
    slurm-3607904.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     31
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-049 | -1701.51458227 eV
    slurm-3607905.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     20

======================================================================
2026-10-19 10:11 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 3
  running: 3
  free slots under limit 34: 31

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 49
  crashed: 1

======================================================================
2026-10-19 10:11 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list crashed
Result: 1 folders

crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
    slurm-59808968.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     53

======================================================================
2026-10-19 10:11 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage submit --status crashed --root /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: finished

Jobs in queue: 3 of limit 34

Folders to submit: 1
  /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
Type yes to save each run and submit: Submitted job 3615421: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010

Submitted: 1

======================================================================
2026-10-19 10:12 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage status
Result: checked

Jobs from this folder: 3
  running: 3

All my jobs in the queue: 4
  pending: 1
  running: 3
  free slots under limit 34: 30

Folders under /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training: 50
  converged: 33
  crashed after reaching accuracy: 1
  ionic not converged: 1
  crashed: 7
  incomplete: 5
  running or pending: 3

Needs a look:
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043 [SCF at NELM]
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047 [SCF at NELM]

======================================================================
2026-10-19 10:12 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage list crashed
Result: 7 folders

crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
    slurm-3614666.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 0.5180 eV/A, max stress 25.59 kB (limit 1.0 kB), last ionic dE 2.68e-01 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019
    slurm-3614680.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 0.6365 eV/A, max stress 11.92 kB (limit 1.0 kB), last ionic dE 6.47e+01 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024
    slurm-3614685.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 1.8847 eV/A, max stress 15.42 kB (limit 1.0 kB), last ionic dE 4.45e+00 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031
    slurm-3614692.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 1.1361 eV/A, max stress 14.10 kB (limit 1.0 kB), last ionic dE 1.80e+01 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034
    slurm-3614737.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 1.5375 eV/A, max stress 27.16 kB (limit 1.0 kB), last ionic dE 2.30e-01 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043
    slurm-3614746.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 1.2065 eV/A, max stress 22.12 kB (limit 1.0 kB), last ionic dE 1.56e+01 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047
    slurm-3614750.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 1.6811 eV/A, max stress 29.78 kB (limit 1.0 kB), last ionic dE 6.26e-01 eV, force limit 0.01 eV/A: criteria not met

======================================================================
2026-10-19 10:12 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage submit --status crashed --root /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
Result: finished

Jobs in queue: 4 of limit 34
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
Warning: ZBRENT: fatal error in bracketing, max force 0.5180 eV/A, max stress 25.59 kB (limit 1.0 kB), last ionic dE 2.68e-01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019
Warning: ZBRENT: fatal error in bracketing, max force 0.6365 eV/A, max stress 11.92 kB (limit 1.0 kB), last ionic dE 6.47e+01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024
Warning: ZBRENT: fatal error in bracketing, max force 1.8847 eV/A, max stress 15.42 kB (limit 1.0 kB), last ionic dE 4.45e+00 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031
Warning: ZBRENT: fatal error in bracketing, max force 1.1361 eV/A, max stress 14.10 kB (limit 1.0 kB), last ionic dE 1.80e+01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034
Warning: ZBRENT: fatal error in bracketing, max force 1.5375 eV/A, max stress 27.16 kB (limit 1.0 kB), last ionic dE 2.30e-01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043
Warning: ZBRENT: fatal error in bracketing, max force 1.2065 eV/A, max stress 22.12 kB (limit 1.0 kB), last ionic dE 1.56e+01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043
Warning: last SCF hit NELM. Fix NELM or ALGO first: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047
Warning: ZBRENT: fatal error in bracketing, max force 1.6811 eV/A, max stress 29.78 kB (limit 1.0 kB), last ionic dE 6.26e-01 eV, force limit 0.01 eV/A: criteria not met: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047

Folders to submit: 7
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043  (CONTCAR to POSCAR)
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
Submitted job 3615424: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019
Submitted job 3615425: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024
Submitted job 3615426: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031
Submitted job 3615427: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034
Submitted job 3615428: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043
Submitted job 3615429: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047
CONTCAR copied to POSCAR: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047
Submitted job 3615430: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047

Submitted: 7

======================================================================
2026-10-19 16:29 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 1 of limit 34

Folders to submit: 8
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-10
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-16
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-17
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-18
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-19
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-7
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-8
  /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-9
Type yes to save each run and submit: Submitted job 3617593: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-10
Submitted job 3617594: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-16
Submitted job 3617595: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-17
Submitted job 3617596: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-18
Submitted job 3617597: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-19
Submitted job 3617598: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-7
Submitted job 3617599: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-8
Submitted job 3617600: /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-9

Submitted: 8

======================================================================
2026-10-19 18:04 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set
$ vtriage submit status not_submitted
Result: failed, exit code 2

usage: resubmit.py [-h] [--status STATUS] [--group GROUP] [--root ROOT]
                   [--list LIST] [--max MAX] [--queue-limit QUEUE_LIMIT]
                   [--force] [--skip-zbrent-met] [--path PATH [PATH ...]]
                   [--yes]
resubmit.py: error: unrecognized arguments: status not_submitted

======================================================================
2026-10-19 18:05 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set
$ vtriage submit --status not_submitted
Result: failed, exit code 1

Error: unknown status. Use one of:
  converged
  crashed after reaching accuracy
  SCF not converged
  ionic not converged
  crashed
  incomplete
  running or pending
  not submitted
  missing inputs

======================================================================
2026-10-19 18:05 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 0 of limit 34
No folders selected.

======================================================================
2026-10-19 18:30 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set
$ vtriage status
Result: checked

Jobs from this folder: 1
  pending: 1

All my jobs in the queue: 1
  pending: 1
  free slots under limit 34: 33

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set: 9
  crashed after reaching accuracy: 6
  incomplete: 2
  running or pending: 1

======================================================================
2026-10-19 18:30 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 9 folders

crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-10
running or pending | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-15
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-16
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-17
incomplete | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-18
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-19
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-7
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-8
crashed after reaching accuracy | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set/str-9

======================================================================
2026-10-20 08:07 | Stampede | /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 34: 34

Folders under /work2/11532/garora/mecx/4-MECx_W10_4vac_6x6x6/random_test_set: 9
  crashed after reaching accuracy: 9

======================================================================
2026-10-20 10:00 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 34: 34

Folders under /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training: 50
  converged: 39
  crashed after reaching accuracy: 1
  ionic not converged: 2
  crashed: 3
  incomplete: 5

Needs a look:
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-027 [SCF at NELM]

======================================================================
2026-10-20 10:00 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage list incomplete
Result: 5 folders

incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-030
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-036
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-042
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-044
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-046

======================================================================
2026-10-20 10:01 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage list crashed
Result: 3 folders

crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-027
    slurm-3614688.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 1.0192 eV/A, max stress 20.84 kB (limit 1.0 kB), last ionic dE 4.51e+00 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-028
    slurm-3614689.out: [2026-10-19T13:01:33.020] error: *** JOB 3614689 ON c517-021 CANCELLED AT 2026-10-19T13:01:33 DUE TO TIME LIMIT ***
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-032
    slurm-3614693.out: [2026-10-19T13:03:02.017] error: *** JOB 3614693 ON c511-073 CANCELLED AT 2026-10-19T13:03:02 DUE TO TIME LIMIT ***

======================================================================
2026-10-20 10:01 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 50 folders

converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-000 | -1775.33201816 eV
    slurm-3614661.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     54
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-001 | -1773.87705045 eV
    slurm-3614662.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     46
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-002 | -1772.17392815 eV
    slurm-3614663.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     44
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-003 | -1773.29082098 eV
    slurm-3614664.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     62
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-004 | -1778.29271734 eV
    slurm-3614665.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     59
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-005 | -1772.65151155 eV
    slurm-3615424.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     60
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-006 | -1774.61325311 eV
    slurm-3614667.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     54
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-007 | -1772.5147532 eV
    slurm-3614668.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     83
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-008 | -1771.87253227 eV
    slurm-3614669.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-009 | -1774.50139158 eV
    slurm-3614670.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     73
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-010 | -1774.92015564 eV
    slurm-3614671.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     42
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-011 | -1774.93663711 eV
    slurm-3614672.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     75
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-012 | -1776.57672681 eV
    slurm-3614673.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     77
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-013 | -1773.8565412 eV
    slurm-3614674.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     45
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-014 | -1779.89487736 eV
    slurm-3614675.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     43
crashed after reaching accuracy | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-015
    slurm-3614676.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     57
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-016 | -1774.85471044 eV
    slurm-3614677.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     58
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-017 | -1767.9183621 eV
    slurm-3614678.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     52
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-018 | -1778.2450224 eV
    slurm-3614679.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     47
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-019 | -1767.07518192 eV
    slurm-3615425.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     73
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-020 | -1777.82399815 eV
    slurm-3614681.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     64
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-021 | -1775.46408714 eV
    slurm-3614682.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     53
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-022 | -1777.3125507 eV
    slurm-3614683.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     62
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-023 | -1775.81651888 eV
    slurm-3614684.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     60
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-024 | -1773.62660788 eV
    slurm-3615426.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     43
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-025 | -1778.83289926 eV
    slurm-3614686.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     63
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-026 | -1773.8806148 eV
    slurm-3614687.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     59
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-027
    slurm-3614688.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 1.0192 eV/A, max stress 20.84 kB (limit 1.0 kB), last ionic dE 4.51e+00 eV, force limit 0.01 eV/A: criteria not met
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-028
    slurm-3614689.out: [2026-10-19T13:01:33.020] error: *** JOB 3614689 ON c517-021 CANCELLED AT 2026-10-19T13:01:33 DUE TO TIME LIMIT ***
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-029 | -1768.68154509 eV
    slurm-3614690.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     57
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-030
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-031 | -1773.07566737 eV
    slurm-3615427.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     85
crashed | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-032
    slurm-3614693.out: [2026-10-19T13:03:02.017] error: *** JOB 3614693 ON c511-073 CANCELLED AT 2026-10-19T13:03:02 DUE TO TIME LIMIT ***
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-033 | -1778.60359576 eV
    slurm-3614694.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     50
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-034 | -1775.98033873 eV
    slurm-3615428.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     61
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-035 | -1775.54093422 eV
    slurm-3614738.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     46
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-036
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-037 | -1772.28507469 eV
    slurm-3614740.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     44
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-038 | -1771.59359316 eV
    slurm-3614741.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     64
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-039 | -1777.50873838 eV
    slurm-3614742.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     58
ionic not converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-040 | -1773.63439304 eV
    slurm-3614743.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     66
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-041 | -1776.89124543 eV
    slurm-3614744.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     48
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-042
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-043 | -1771.17290949 eV
    slurm-3615429.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     76
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-044
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-045 | -1771.37391245 eV
    slurm-3614748.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     76
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-046
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-047 | -1778.41541128 eV
    slurm-3615430.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     70
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-048 | -1775.52319412 eV
    slurm-3614751.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     48
converged | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-049 | -1774.55054259 eV
    slurm-3614752.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     85

======================================================================
2026-10-20 10:01 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage list incomplete
Result: 5 folders

incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-030
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-036
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-042
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-044
incomplete | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-046

======================================================================
2026-10-20 10:01 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage status /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 34: 34

Folders under /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training: 50
  converged: 39
  crashed after reaching accuracy: 1
  ionic not converged: 2
  crashed: 3
  incomplete: 5

Needs a look:
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-027 [SCF at NELM]

======================================================================
2026-10-20 10:01 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
$ vtriage submit --status incomplete --root /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training
Result: finished

Jobs in queue: 0 of limit 34

Folders to submit: 5
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-030
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-036
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-042
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-044
  /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-046
Type yes to save each run and submit: Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-030
Submitted job 3620671: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-030
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-036
Submitted job 3620672: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-036
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-042
Submitted job 3620674: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-042
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-044
Submitted job 3620675: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-044
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-046
Submitted job 3620676: /work2/11532/garora/mecx/Mo-based-alloys/2-Mo30/1-DFT_training/str-046

Submitted: 5

======================================================================
2026-10-20 10:52 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 5
  pending: 5
  free slots under limit 34: 29

Folders under /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training: 50
  converged: 49
  crashed: 1

======================================================================
2026-10-20 10:52 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list crashed
Result: 1 folders

crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
    slurm-59808968.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     53

======================================================================
2026-10-20 10:53 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage history /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
Result: finished

Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-000
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-003
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-004
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-005
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-007
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-008
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-009
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-011
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-012
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-013
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-014
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-015
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-017
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-018
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-019
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-020
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-021
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-022
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-023
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-024
Archived as run 2: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025
Archived as run 2: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-027
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-028
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-029
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-030
Archived as run 3: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-032
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-033
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-034
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-035
Archived as run 2: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-037
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-038
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-039
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-040
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-041
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-042
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-043
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-044
Archived as run 2: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-046
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-047
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-048
Archived as run 1: /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-049

Summary:
  archived: 45
  skipped: 5

======================================================================
2026-10-20 10:53 | Stampede | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 50 folders

converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-000 | -1708.39491847 eV
    slurm-59808927.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     58
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-001 | -1711.61521207 eV
    slurm-59808930.out: ZBRENT: fatal error in bracketing
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-002 | -1702.08029896 eV
    slurm-59808932.out: ZBRENT: fatal error in bracketing
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-003 | -1709.13253273 eV
    slurm-59808955.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     34
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-004 | -1714.68851728 eV
    slurm-59808962.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-005 | -1717.20083513 eV
    slurm-59808963.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     50
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-006 | -1702.76987321 eV
    slurm-59808964.out: ZBRENT: fatal error in bracketing
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-007 | -1708.55168419 eV
    slurm-59808965.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     32
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-008 | -1704.55455042 eV
    slurm-59808966.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     35
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-009 | -1709.98959376 eV
    slurm-59808967.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
crashed | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-010
    slurm-59808968.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     53
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-011 | -1708.96493868 eV
    slurm-59808969.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     42
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-012 | -1709.66145664 eV
    slurm-59808970.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     52
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-013 | -1708.46253298 eV
    slurm-59808971.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     36
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-014 | -1705.83494126 eV
    slurm-59852428.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     25
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-015 | -1704.06225855 eV
    slurm-59852433.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     15
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-016 | -1704.29592618 eV
    slurm-59852436.out: [2026-10-16T21:48:34.693] error: *** STEP 59852436.0 ON nid006602 CANCELLED AT 2026-10-16T21:48:34 DUE TO TASK FAILURE ***
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-017 | -1708.07253746 eV
    slurm-59852439.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     25
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-018 | -1714.32038232 eV
    slurm-3606857.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     18
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-019 | -1707.82251126 eV
    slurm-3606858.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     28
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-020 | -1703.6065572 eV
    slurm-3606859.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     35
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-021 | -1704.11681592 eV
    slurm-3606860.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     24
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-022 | -1708.66928734 eV
    slurm-3606861.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     37
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-023 | -1710.81056446 eV
    slurm-3606862.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-024 | -1711.29957235 eV
    slurm-3606863.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     17
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-025 | -1704.34732305 eV
    slurm-3608661.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     31
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-026 | -1708.13004379 eV
    slurm-3610744.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     34
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-027 | -1713.26102327 eV
    slurm-3606866.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     22
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-028 | -1712.22828585 eV
    slurm-3606867.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     42
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-029 | -1709.63739725 eV
    slurm-3606868.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-030 | -1709.82041787 eV
    slurm-3606869.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     28
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-031 | -1706.3432091 eV
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-032 | -1706.30225402 eV
    slurm-3606871.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     32
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-033 | -1709.48768838 eV
    slurm-3606872.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     31
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-034 | -1709.26609787 eV
    slurm-3606873.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     19
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-035 | -1710.09393135 eV
    slurm-3606874.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     29
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-036 | -1709.93823455 eV
    slurm-3610741.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     17
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-037 | -1704.50150404 eV
    slurm-3607893.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     32
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-038 | -1707.47176164 eV
    slurm-3607894.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     41
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-039 | -1712.29407631 eV
    slurm-3607895.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     29
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-040 | -1705.62514348 eV
    slurm-3607896.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-041 | -1711.17453534 eV
    slurm-3607897.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     38
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-042 | -1715.76265433 eV
    slurm-3607898.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     35
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-043 | -1712.7202947 eV
    slurm-3607899.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     28
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-044 | -1715.33804615 eV
    slurm-3607900.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     30
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-045 | -1706.48243531 eV
    slurm-3610742.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     33
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-046 | -1715.58754637 eV
    slurm-3607902.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     41
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-047 | -1710.22157874 eV
    slurm-3607903.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     39
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-048 | -1710.80572373 eV
    slurm-3607904.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     31
converged | /work2/11532/garora/mecx/Mo-based-alloys/1-Mo28/1-DFT_training/str-049 | -1701.51458227 eV
    slurm-3607905.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     20


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

======================================================================
2026-10-11 07:09 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 2 folders

crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS
    slurm-59632926.out: [2026-10-10T22:13:11.779] error: Detected 1 oom_kill event in StepId=59632926.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC
    slurm-59632854.out: [2026-10-11T06:35:39.886] error: Detected 1 oom_kill event in StepId=59632854.0. Some of the step tasks have been OOM Killed.

======================================================================
2026-10-11 07:10 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 15: 15

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  crashed after reaching accuracy: 2

======================================================================
2026-10-11 07:10 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage history /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: finished

Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC

Summary:
  archived: 2

======================================================================
2026-10-11 07:10 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage submit --status crashed after reaching accuracy --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: finished

Jobs in queue: 0 of limit 15
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC

Folders to submit: 2
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC  (CONTCAR to POSCAR)
Type yes to save each run and submit: CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS
Submitted job 59671003: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/1-SQS
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC
Submitted job 59671004: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/1-relaxing/2-MEC

Submitted: 2

======================================================================
2026-10-11 09:30 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
Result: checked

Jobs from this folder: 2
  pending: 1
  running: 1

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  running or pending: 2

======================================================================
2026-10-11 09:38 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/vt_test: 10
  not submitted: 10

======================================================================
2026-10-11 09:40 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/vt_test
Result: finished

Jobs in queue: 2 of limit 15

Folders to submit: 10
  /pscratch/sd/g/garora/vt_test/C11/1
  /pscratch/sd/g/garora/vt_test/C11/2
  /pscratch/sd/g/garora/vt_test/C11/3
  /pscratch/sd/g/garora/vt_test/C11/4
  /pscratch/sd/g/garora/vt_test/C11/5
  /pscratch/sd/g/garora/vt_test/C11/6
  /pscratch/sd/g/garora/vt_test/C12/1
  /pscratch/sd/g/garora/vt_test/C12/2
  /pscratch/sd/g/garora/vt_test/C44/x
  /pscratch/sd/g/garora/vt_test/C44/y
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-11 09:42 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/vt_test --path=C11/{2..6}
Result: finished

Jobs in queue: 2 of limit 15
Path filter kept 5 of 10 folders.

Folders to submit: 5
  /pscratch/sd/g/garora/vt_test/C11/2
  /pscratch/sd/g/garora/vt_test/C11/3
  /pscratch/sd/g/garora/vt_test/C11/4
  /pscratch/sd/g/garora/vt_test/C11/5
  /pscratch/sd/g/garora/vt_test/C11/6
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-11 09:43 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/vt_test --path=C77
Result: finished

Jobs in queue: 2 of limit 15
No selected folder matches: C77
Path filter kept 0 of 10 folders.
No folders selected.

======================================================================
2026-10-11 09:45 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage edit --status not submitted --root /pscratch/sd/g/garora/vt_test --set NCORE=32
Result: finished


/pscratch/sd/g/garora/vt_test/C11/1
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C11/2
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C11/3
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C11/4
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C11/5
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C11/6
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C12/1
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C12/2
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C44/x
  NCORE: 16 -> 32

/pscratch/sd/g/garora/vt_test/C44/y
  NCORE: 16 -> 32

Folders to change: 10
Type yes to save each run and apply the changes: Changed: /pscratch/sd/g/garora/vt_test/C11/1
Changed: /pscratch/sd/g/garora/vt_test/C11/2
Changed: /pscratch/sd/g/garora/vt_test/C11/3
Changed: /pscratch/sd/g/garora/vt_test/C11/4
Changed: /pscratch/sd/g/garora/vt_test/C11/5
Changed: /pscratch/sd/g/garora/vt_test/C11/6
Changed: /pscratch/sd/g/garora/vt_test/C12/1
Changed: /pscratch/sd/g/garora/vt_test/C12/2
Changed: /pscratch/sd/g/garora/vt_test/C44/x
Changed: /pscratch/sd/g/garora/vt_test/C44/y

======================================================================
2026-10-11 09:55 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/vt_test: 10
  not submitted: 10

======================================================================
2026-10-11 09:55 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/vt_test: 10
  not submitted: 10

======================================================================
2026-10-11 09:56 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/vt_test: 10
  not submitted: 10

======================================================================
2026-10-11 09:56 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/vt_test: 10
  not submitted: 10

======================================================================
2026-10-11 09:58 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/vt_test: 10
  not submitted: 10

======================================================================
2026-10-11 09:58 | perlmutter | /pscratch/sd/g/garora/vt_test/C11
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  pending: 1
  running: 1
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/vt_test/C11: 6
  not submitted: 6

======================================================================
2026-10-11 10:17 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage edit --status not submitted --remove KPAR --remove NCORE --remove LCHARGE --set NSW=0 --set EDIFF=1E-05 --set LREAL=.FALSE.
Result: finished


/pscratch/sd/g/garora/vt_test/C11/1
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C11/2
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C11/3
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C11/4
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C11/5
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C11/6
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C12/1
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C12/2
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C44/x
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

/pscratch/sd/g/garora/vt_test/C44/y
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 32)

Folders to change: 10
Type yes to save each run and apply the changes: Changed: /pscratch/sd/g/garora/vt_test/C11/1
Changed: /pscratch/sd/g/garora/vt_test/C11/2
Changed: /pscratch/sd/g/garora/vt_test/C11/3
Changed: /pscratch/sd/g/garora/vt_test/C11/4
Changed: /pscratch/sd/g/garora/vt_test/C11/5
Changed: /pscratch/sd/g/garora/vt_test/C11/6
Changed: /pscratch/sd/g/garora/vt_test/C12/1
Changed: /pscratch/sd/g/garora/vt_test/C12/2
Changed: /pscratch/sd/g/garora/vt_test/C44/x
Changed: /pscratch/sd/g/garora/vt_test/C44/y

======================================================================
2026-10-11 10:17 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage edit --status not submitted --path C12/* --set NSW=1 --set IBRION=2
Result: finished

Path filter kept 2 of 10 folders.

/pscratch/sd/g/garora/vt_test/C12/1
  IBRION: 1 -> 2
  NSW: 0 -> 1

/pscratch/sd/g/garora/vt_test/C12/2
  IBRION: 1 -> 2
  NSW: 0 -> 1

Folders to change: 2
Type yes to save each run and apply the changes: Changed: /pscratch/sd/g/garora/vt_test/C12/1
Changed: /pscratch/sd/g/garora/vt_test/C12/2

======================================================================
2026-10-11 10:20 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 3 jobs

2026-10-11 10:20 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 3
  /pscratch/sd/g/garora/vt_test/C11/1
  /pscratch/sd/g/garora/vt_test/C11/2
  /pscratch/sd/g/garora/vt_test/C11/3
Not submitted now because of the limits: 7
Confirmed by --yes.
sbatch failed in /pscratch/sd/g/garora/vt_test/C11/1
  sbatch: error: Job cost estimated at 0.17 node hours, your balance is 0.00 node hours (Repo: 0.00 node hours). Cannot proceed, please see https://docs.nersc.gov/jobs/policy/ for your options to run this job.
sbatch: error: Batch job submission failed: Unspecified error
sbatch failed in /pscratch/sd/g/garora/vt_test/C11/2
  sbatch: error: Job cost estimated at 0.17 node hours, your balance is 0.00 node hours (Repo: 0.00 node hours). Cannot proceed, please see https://docs.nersc.gov/jobs/policy/ for your options to run this job.
sbatch: error: Batch job submission failed: Unspecified error
sbatch failed in /pscratch/sd/g/garora/vt_test/C11/3
  sbatch: error: Job cost estimated at 0.17 node hours, your balance is 0.00 node hours (Repo: 0.00 node hours). Cannot proceed, please see https://docs.nersc.gov/jobs/policy/ for your options to run this job.
sbatch: error: Batch job submission failed: Unspecified error

Submitted: 0
Run the same command again later for the next batch.

======================================================================
2026-10-11 10:21 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 3 jobs

2026-10-11 10:20 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 3
  /pscratch/sd/g/garora/vt_test/C11/1
  /pscratch/sd/g/garora/vt_test/C11/2
  /pscratch/sd/g/garora/vt_test/C11/3
Not submitted now because of the limits: 7
Confirmed by --yes.
Submitted job 59675578: /pscratch/sd/g/garora/vt_test/C11/1
Submitted job 59675579: /pscratch/sd/g/garora/vt_test/C11/2
Submitted job 59675580: /pscratch/sd/g/garora/vt_test/C11/3

Submitted: 3
Run the same command again later for the next batch.

======================================================================
2026-10-11 10:28 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 3 jobs

2026-10-11 10:28 folders: 10, not submitted: 7, in queue: 0

Folders to submit: 3
  /pscratch/sd/g/garora/vt_test/C11/4
  /pscratch/sd/g/garora/vt_test/C11/5
  /pscratch/sd/g/garora/vt_test/C11/6
Not submitted now because of the limits: 4
Confirmed by --yes.
Submitted job 59675701: /pscratch/sd/g/garora/vt_test/C11/4
Submitted job 59675702: /pscratch/sd/g/garora/vt_test/C11/5
Submitted job 59675703: /pscratch/sd/g/garora/vt_test/C11/6

Submitted: 3
Run the same command again later for the next batch.

======================================================================
2026-10-11 10:30 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 7 jobs

2026-10-11 10:30 folders: 10, not submitted: 4, in queue: 0

Folders to submit: 4
  /pscratch/sd/g/garora/vt_test/C12/1
  /pscratch/sd/g/garora/vt_test/C12/2
  /pscratch/sd/g/garora/vt_test/C44/x
  /pscratch/sd/g/garora/vt_test/C44/y
Confirmed by --yes.
Submitted job 59675744: /pscratch/sd/g/garora/vt_test/C12/1
Submitted job 59675745: /pscratch/sd/g/garora/vt_test/C12/2
Submitted job 59675746: /pscratch/sd/g/garora/vt_test/C44/x
Submitted job 59675747: /pscratch/sd/g/garora/vt_test/C44/y

Submitted: 4

======================================================================
2026-10-11 10:33 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto finish
Result: campaign done

vasp_triage auto agent finished
Date: 2026-10-11 10:33
Root: /pscratch/sd/g/garora/vt_test
Path patterns: none, every folder

Folders: 10
  converged: 8
  ionic not converged: 2

Folders that need a look: 2
  ionic not converged | /pscratch/sd/g/garora/vt_test/C12/1
  ionic not converged | /pscratch/sd/g/garora/vt_test/C12/2

Email: Submitted batch job 59675808, to gauravarora.1100@gmail.com

======================================================================
2026-10-11 10:40 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 2
  running: 2
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/vt_test: 0

======================================================================
2026-10-11 10:55 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 3 jobs

2026-10-11 10:55 folders: 11, not submitted: 11, in queue: 0

Folders to submit: 3
  /pscratch/sd/g/garora/vt_test
  /pscratch/sd/g/garora/vt_test/C11/1
  /pscratch/sd/g/garora/vt_test/C11/2
Not submitted now because of the limits: 8
Confirmed by --yes.
sbatch failed in /pscratch/sd/g/garora/vt_test
  sbatch: error: Job cost estimated at 0.17 node hours, your balance is 0.00 node hours (Repo: 0.00 node hours). Cannot proceed, please see https://docs.nersc.gov/jobs/policy/ for your options to run this job.
sbatch: error: Batch job submission failed: Unspecified error
sbatch failed in /pscratch/sd/g/garora/vt_test/C11/1
  sbatch: error: Job cost estimated at 0.17 node hours, your balance is 0.00 node hours (Repo: 0.00 node hours). Cannot proceed, please see https://docs.nersc.gov/jobs/policy/ for your options to run this job.
sbatch: error: Batch job submission failed: Unspecified error
sbatch failed in /pscratch/sd/g/garora/vt_test/C11/2
  sbatch: error: Job cost estimated at 0.17 node hours, your balance is 0.00 node hours (Repo: 0.00 node hours). Cannot proceed, please see https://docs.nersc.gov/jobs/policy/ for your options to run this job.
sbatch: error: Batch job submission failed: Unspecified error

Submitted: 0
Run the same command again later for the next batch.

======================================================================
2026-10-11 10:55 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage edit --status not submitted --remove KPAR --remove NCORE --remove LCHARGE --set NSW=0 --set EDIFF=1E-05 --set LREAL=.FALSE.
Result: finished


/pscratch/sd/g/garora/vt_test
  LREAL: .FALSE.       (Projection operators: automatic) -> .FALSE.
  EDIFF: 1E-08        (SCF energy convergence, in eV) -> 1E-05
  NSW: 100          (Max ionic steps) -> 0

/pscratch/sd/g/garora/vt_test/C11/1
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C11/2
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C11/3
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C11/4
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C11/5
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C11/6
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C12/1
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C12/2
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C44/x
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

/pscratch/sd/g/garora/vt_test/C44/y
  EDIFF: 1E-07 -> 1E-05
  NSW: 100 -> 0
  LREAL: Auto -> .FALSE.
  remove LCHARGE (was .FALSE)
  remove KPAR (was 14)
  remove NCORE (was 16)

Folders to change: 11
Type yes to save each run and apply the changes: Changed: /pscratch/sd/g/garora/vt_test
Changed: /pscratch/sd/g/garora/vt_test/C11/1
Changed: /pscratch/sd/g/garora/vt_test/C11/2
Changed: /pscratch/sd/g/garora/vt_test/C11/3
Changed: /pscratch/sd/g/garora/vt_test/C11/4
Changed: /pscratch/sd/g/garora/vt_test/C11/5
Changed: /pscratch/sd/g/garora/vt_test/C11/6
Changed: /pscratch/sd/g/garora/vt_test/C12/1
Changed: /pscratch/sd/g/garora/vt_test/C12/2
Changed: /pscratch/sd/g/garora/vt_test/C44/x
Changed: /pscratch/sd/g/garora/vt_test/C44/y

======================================================================
2026-10-11 10:55 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage edit --status not submitted --path C12/* --set NSW=1 --set IBRION=2
Result: finished

Path filter kept 2 of 11 folders.

/pscratch/sd/g/garora/vt_test/C12/1
  IBRION: 1 -> 2
  NSW: 0 -> 1

/pscratch/sd/g/garora/vt_test/C12/2
  IBRION: 1 -> 2
  NSW: 0 -> 1

Folders to change: 2
Type yes to save each run and apply the changes: Changed: /pscratch/sd/g/garora/vt_test/C12/1
Changed: /pscratch/sd/g/garora/vt_test/C12/2

======================================================================
2026-10-11 11:00 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 3 jobs

2026-10-11 11:00 folders: 11, not submitted: 11, in queue: 0

Folders to submit: 3
  /pscratch/sd/g/garora/vt_test
  /pscratch/sd/g/garora/vt_test/C11/1
  /pscratch/sd/g/garora/vt_test/C11/2
Not submitted now because of the limits: 8
Confirmed by --yes.
Submitted job 59676377: /pscratch/sd/g/garora/vt_test
Submitted job 59676379: /pscratch/sd/g/garora/vt_test/C11/1
Submitted job 59676380: /pscratch/sd/g/garora/vt_test/C11/2

Submitted: 3
Run the same command again later for the next batch.

======================================================================
2026-10-11 11:05 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 3 jobs

2026-10-11 11:05 folders: 11, not submitted: 8, in queue: 0

Folders to submit: 3
  /pscratch/sd/g/garora/vt_test/C11/3
  /pscratch/sd/g/garora/vt_test/C11/4
  /pscratch/sd/g/garora/vt_test/C11/5
Not submitted now because of the limits: 5
Confirmed by --yes.
Submitted job 59676470: /pscratch/sd/g/garora/vt_test/C11/3
Submitted job 59676472: /pscratch/sd/g/garora/vt_test/C11/4
Submitted job 59676476: /pscratch/sd/g/garora/vt_test/C11/5

Submitted: 3
Run the same command again later for the next batch.

======================================================================
2026-10-11 11:10 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 3 jobs

2026-10-11 11:10 folders: 11, not submitted: 5, in queue: 0

Folders to submit: 3
  /pscratch/sd/g/garora/vt_test/C11/6
  /pscratch/sd/g/garora/vt_test/C12/1
  /pscratch/sd/g/garora/vt_test/C12/2
Not submitted now because of the limits: 2
Confirmed by --yes.
Submitted job 59676577: /pscratch/sd/g/garora/vt_test/C11/6
Submitted job 59676580: /pscratch/sd/g/garora/vt_test/C12/1
Submitted job 59676581: /pscratch/sd/g/garora/vt_test/C12/2

Submitted: 3
Run the same command again later for the next batch.

======================================================================
2026-10-11 11:15 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto submit
Result: up to 3 jobs

2026-10-11 11:15 folders: 11, not submitted: 2, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_test/C44/x
  /pscratch/sd/g/garora/vt_test/C44/y
Confirmed by --yes.
Submitted job 59676672: /pscratch/sd/g/garora/vt_test/C44/x
Submitted job 59676673: /pscratch/sd/g/garora/vt_test/C44/y

Submitted: 2

======================================================================
2026-10-11 11:20 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage auto finish
Result: campaign done

vasp_triage auto agent finished
Date: 2026-10-11 11:20
Root: /pscratch/sd/g/garora/vt_test
Path patterns: none, every folder

Folders: 11
  converged: 9
  ionic not converged: 2

Folders that need a look: 2
  ionic not converged | /pscratch/sd/g/garora/vt_test/C12/1
  ionic not converged | /pscratch/sd/g/garora/vt_test/C12/2

Email: Submitted batch job 59676793, to gauravarora.1100@gmail.com

======================================================================
2026-10-11 11:26 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 3
  pending: 1
  running: 2
  free slots under limit 15: 12

Folders under /pscratch/sd/g/garora/vt_test: 11
  converged: 9
  ionic not converged: 2

======================================================================
2026-10-11 13:40 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage submit --status converged --path C11/*
Result: finished

Jobs in queue: 0 of limit 15
Path filter kept 6 of 9 folders.
Converged, skipped (use --force): /pscratch/sd/g/garora/vt_test/C11/1
Converged, skipped (use --force): /pscratch/sd/g/garora/vt_test/C11/2
Converged, skipped (use --force): /pscratch/sd/g/garora/vt_test/C11/3
Converged, skipped (use --force): /pscratch/sd/g/garora/vt_test/C11/4
Converged, skipped (use --force): /pscratch/sd/g/garora/vt_test/C11/5
Converged, skipped (use --force): /pscratch/sd/g/garora/vt_test/C11/6
Nothing to submit.

======================================================================
2026-10-11 13:40 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 15: 15

Folders under /pscratch/sd/g/garora/vt_test: 11
  converged: 9
  ionic not converged: 2

======================================================================
2026-10-12 10:30 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 15: 15

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 2
  crashed after reaching accuracy: 2

======================================================================
2026-10-12 10:37 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS
Result: finished

Jobs in queue: 0 of limit 15

Folders to submit: 15
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_-2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_-2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_-2%
Type yes to save each run and submit: Submitted job 59707138: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+0%
Submitted job 59707139: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+1%
Submitted job 59707140: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+2%
Submitted job 59707141: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_-1%
Submitted job 59707142: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_-2%
Submitted job 59707143: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+0%
Submitted job 59707144: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+1%
Submitted job 59707145: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+2%
Submitted job 59707146: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_-1%
Submitted job 59707147: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_-2%
Submitted job 59707148: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+0%
Submitted job 59707149: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+1%
Submitted job 59707150: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+2%
Submitted job 59707151: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_-1%
Submitted job 59707152: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_-2%

Submitted: 15

======================================================================
2026-10-12 12:09 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic
$ vtriage status
Result: checked

Jobs from this folder: 13
  pending: 11
  running: 2

All my jobs in the queue: 13
  pending: 11
  running: 2
  free slots under limit 15: 2

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic: 16
  running or pending: 13
  not submitted: 2
  missing inputs: 1

======================================================================
2026-10-12 12:14 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

Jobs from this folder: 13
  pending: 11
  running: 2

All my jobs in the queue: 13
  pending: 11
  running: 2
  free slots under limit 15: 2

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 18
  crashed after reaching accuracy: 2
  running or pending: 13
  not submitted: 2
  missing inputs: 1

======================================================================
2026-10-12 14:03 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

Jobs from this folder: 13
  pending: 7
  running: 6

All my jobs in the queue: 14
  pending: 7
  running: 7
  free slots under limit 15: 1

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 18
  crashed after reaching accuracy: 2
  running or pending: 13
  not submitted: 2
  missing inputs: 1

======================================================================
2026-10-12 14:04 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac
$ vtriage status
Result: checked

Jobs from this folder: 13
  pending: 7
  running: 6

All my jobs in the queue: 14
  pending: 7
  running: 7
  free slots under limit 15: 1

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac: 18
  crashed after reaching accuracy: 2
  running or pending: 13
  not submitted: 2
  missing inputs: 1

======================================================================
2026-10-12 14:56 | perlmutter | /pscratch/sd/g/garora/vt_test
$ vtriage status /pscratch/sd/g/garora/vt_test
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 14
  pending: 6
  running: 8
  free slots under limit 15: 1

Folders under /pscratch/sd/g/garora/vt_test: 11
  converged: 9
  ionic not converged: 2

======================================================================
2026-10-12 15:02 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 13
  pending: 6
  running: 7
  free slots under limit 15: 2

Folders under /pscratch/sd/g/garora/vt_sched: 10
  not submitted: 10

======================================================================
2026-10-12 15:04 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage schedule --every 5m --batch 2 --queue-limit 20
Result: finished

Schedule plan for /pscratch/sd/g/garora/vt_sched
  folders: 10, not submitted: 10, in queue: 0
  every 5m: */5 * * * * (times are UTC)
  new jobs per cycle: 2, queue limit: 20
  path patterns: none, every folder
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_sched
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/vt_sched/auto_cron.log
  #SCRON --open-mode=append
  */5 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_sched --batch 2 --queue-limit 20

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/vt_sched/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/vt_sched

======================================================================
2026-10-12 15:05 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 15:05 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched/C11/1
  /pscratch/sd/g/garora/vt_sched/C11/2
Not submitted now because of the limits: 8
Confirmed by --yes.
Submitted job 59713644: /pscratch/sd/g/garora/vt_sched/C11/1
Submitted job 59713652: /pscratch/sd/g/garora/vt_sched/C11/2

Submitted: 2
Run the same command again later for the next batch.

======================================================================
2026-10-12 15:05 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage confirm
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_sched
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/vt_sched/auto_cron.log
  #SCRON --open-mode=append
  */5 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_sched --batch 2 --queue-limit 20
Old table saved in /pscratch/sd/g/garora/vt_sched/scrontab_backup_20261012_150532.txt

Running the first cycle now.
2026-10-12 15:05 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched/C11/1
  /pscratch/sd/g/garora/vt_sched/C11/2
Not submitted now because of the limits: 8
Confirmed by --yes.
Submitted job 59713644: /pscratch/sd/g/garora/vt_sched/C11/1
Submitted job 59713652: /pscratch/sd/g/garora/vt_sched/C11/2

Submitted: 2
Run the same command again later for the next batch.

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/vt_sched/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-12 15:10 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 15:10 folders: 10, not submitted: 8, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched/C11/3
  /pscratch/sd/g/garora/vt_sched/C11/4
Not submitted now because of the limits: 6
Confirmed by --yes.
Submitted job 59713783: /pscratch/sd/g/garora/vt_sched/C11/3
Submitted job 59713784: /pscratch/sd/g/garora/vt_sched/C11/4

Submitted: 2
Run the same command again later for the next batch.

======================================================================
2026-10-12 15:15 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 15:15 folders: 10, not submitted: 6, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched/C11/5
  /pscratch/sd/g/garora/vt_sched/C11/6
Not submitted now because of the limits: 4
Confirmed by --yes.
Submitted job 59713845: /pscratch/sd/g/garora/vt_sched/C11/5
Submitted job 59713847: /pscratch/sd/g/garora/vt_sched/C11/6

Submitted: 2
Run the same command again later for the next batch.

======================================================================
2026-10-12 15:20 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 15:20 folders: 10, not submitted: 4, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched/C12/1
  /pscratch/sd/g/garora/vt_sched/C12/2
Not submitted now because of the limits: 2
Confirmed by --yes.
Submitted job 59713928: /pscratch/sd/g/garora/vt_sched/C12/1
Submitted job 59713929: /pscratch/sd/g/garora/vt_sched/C12/2

Submitted: 2
Run the same command again later for the next batch.

======================================================================
2026-10-12 15:25 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 15:25 folders: 10, not submitted: 2, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched/C44/x
  /pscratch/sd/g/garora/vt_sched/C44/y
Confirmed by --yes.
Submitted job 59714014: /pscratch/sd/g/garora/vt_sched/C44/x
Submitted job 59714015: /pscratch/sd/g/garora/vt_sched/C44/y

Submitted: 2

======================================================================
2026-10-12 15:30 | perlmutter | /pscratch/sd/g/garora/vt_sched
$ vtriage auto finish
Result: campaign done

vasp_triage auto agent finished
Date: 2026-10-12 15:30
Root: /pscratch/sd/g/garora/vt_sched
Path patterns: none, every folder

Folders: 10
  converged: 8
  ionic not converged: 2

Folders that need a look: 2
  ionic not converged | /pscratch/sd/g/garora/vt_sched/C12/1
  ionic not converged | /pscratch/sd/g/garora/vt_sched/C12/2

Email: Submitted batch job 59714115, to gauravarora.1100@gmail.com

======================================================================
2026-10-12 16:43 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 13
  pending: 3
  running: 10
  free slots under limit 15: 2

Folders under /pscratch/sd/g/garora/vt_sched2: 10
  not submitted: 10

======================================================================
2026-10-12 16:44 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage schedule --every 10m --batch 2 --queue-limit 20
Result: finished

Schedule plan for /pscratch/sd/g/garora/vt_sched2
  folders: 10, not submitted: 10, in queue: 0
  every 10m: */10 * * * * (times are UTC)
  new jobs per cycle: 2, queue limit: 20
  path patterns: none, every folder
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_sched2
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/vt_sched2/auto_cron.log
  #SCRON --open-mode=append
  */10 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_sched2 --batch 2 --queue-limit 20

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/vt_sched2/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/vt_sched2

======================================================================
2026-10-12 16:45 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 16:45 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched2/C11/1
  /pscratch/sd/g/garora/vt_sched2/C11/2
Not submitted now because of the limits: 8
Confirmed by --yes.
Submitted job 59716065: /pscratch/sd/g/garora/vt_sched2/C11/1
Submitted job 59716066: /pscratch/sd/g/garora/vt_sched2/C11/2

Submitted: 2
Run the same command again later for the next batch.

======================================================================
2026-10-12 16:45 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage confirm --root /pscratch/sd/g/garora/vt_sched2
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_sched2
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/vt_sched2/auto_cron.log
  #SCRON --open-mode=append
  */10 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_sched2 --batch 2 --queue-limit 20
Old table saved in /pscratch/sd/g/garora/vt_sched2/scrontab_backup_20261012_164535.txt

Running the first cycle now.
2026-10-12 16:45 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched2/C11/1
  /pscratch/sd/g/garora/vt_sched2/C11/2
Not submitted now because of the limits: 8
Confirmed by --yes.
Submitted job 59716065: /pscratch/sd/g/garora/vt_sched2/C11/1
Submitted job 59716066: /pscratch/sd/g/garora/vt_sched2/C11/2

Submitted: 2
Run the same command again later for the next batch.

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/vt_sched2/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-12 16:50 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 16:50 folders: 10, not submitted: 8, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched2/C11/3
  /pscratch/sd/g/garora/vt_sched2/C11/4
Not submitted now because of the limits: 6
Confirmed by --yes.
Submitted job 59716298: /pscratch/sd/g/garora/vt_sched2/C11/3
Submitted job 59716299: /pscratch/sd/g/garora/vt_sched2/C11/4

Submitted: 2
Run the same command again later for the next batch.

======================================================================
2026-10-12 17:00 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 17:00 folders: 10, not submitted: 6, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched2/C11/5
  /pscratch/sd/g/garora/vt_sched2/C11/6
Not submitted now because of the limits: 4
Confirmed by --yes.
Submitted job 59716607: /pscratch/sd/g/garora/vt_sched2/C11/5
Submitted job 59716608: /pscratch/sd/g/garora/vt_sched2/C11/6

Submitted: 2
Run the same command again later for the next batch.

======================================================================
2026-10-12 17:10 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 17:10 folders: 10, not submitted: 4, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched2/C12/1
  /pscratch/sd/g/garora/vt_sched2/C12/2
Not submitted now because of the limits: 2
Confirmed by --yes.
Submitted job 59716960: /pscratch/sd/g/garora/vt_sched2/C12/1
Submitted job 59716966: /pscratch/sd/g/garora/vt_sched2/C12/2

Submitted: 2
Run the same command again later for the next batch.

======================================================================
2026-10-12 17:20 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage auto submit
Result: up to 2 jobs

2026-10-12 17:20 folders: 10, not submitted: 2, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/vt_sched2/C44/x
  /pscratch/sd/g/garora/vt_sched2/C44/y
Confirmed by --yes.
Submitted job 59717397: /pscratch/sd/g/garora/vt_sched2/C44/x
Submitted job 59717399: /pscratch/sd/g/garora/vt_sched2/C44/y

Submitted: 2

======================================================================
2026-10-12 17:30 | perlmutter | /pscratch/sd/g/garora/vt_sched2
$ vtriage auto finish
Result: campaign done

vasp_triage auto agent finished
Date: 2026-10-12 17:30
Root: /pscratch/sd/g/garora/vt_sched2
Path patterns: none, every folder

Folders: 10
  converged: 8
  ionic not converged: 2

Folders that need a look: 2
  ionic not converged | /pscratch/sd/g/garora/vt_sched2/C12/1
  ionic not converged | /pscratch/sd/g/garora/vt_sched2/C12/2

Email: Submitted batch job 59717643, to gauravarora.1100@gmail.com

======================================================================
2026-10-12 19:44 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage schedule
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
  folders: 15, not submitted: 15, in queue: 0
  every 5h: 7 */5 * * * (times are UTC)
  Note: 5 does not divide 24, so the gap across midnight UTC is shorter.
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC

======================================================================
2026-10-12 19:50 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage schedule
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
  folders: 15, not submitted: 15, in queue: 0
  every 5h: 7 */5 * * * (times are UTC)
  Note: 5 does not divide 24, so the gap across midnight UTC is shorter.
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC

======================================================================
2026-10-12 19:52 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage schedule
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
  folders: 15, not submitted: 15, in queue: 0
  every 5h: 7 */5 * * * (times are UTC)
  Note: 5 does not divide 24, so the gap across midnight UTC is shorter.
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC

======================================================================
2026-10-12 19:53 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage auto submit
Result: up to 17 jobs

2026-10-12 19:52 folders: 15, not submitted: 15, in queue: 0

Folders to submit: 15
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%
Confirmed by --yes.
Submitted job 59721012: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
Submitted job 59721013: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
Submitted job 59721015: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
Submitted job 59721017: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
Submitted job 59721018: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
Submitted job 59721019: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
Submitted job 59721020: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
Submitted job 59721021: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
Submitted job 59721022: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
Submitted job 59721024: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
Submitted job 59721025: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
Submitted job 59721026: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
Submitted job 59721028: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
Submitted job 59721029: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
Submitted job 59721031: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%

Submitted: 15

======================================================================
2026-10-12 19:53 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage confirm --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
Old table saved in /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/scrontab_backup_20261012_195251.txt

Running the first cycle now.
2026-10-12 19:52 folders: 15, not submitted: 15, in queue: 0

Folders to submit: 15
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%
Confirmed by --yes.
Submitted job 59721012: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
Submitted job 59721013: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
Submitted job 59721015: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
Submitted job 59721017: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
Submitted job 59721018: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
Submitted job 59721019: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
Submitted job 59721020: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
Submitted job 59721021: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
Submitted job 59721022: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
Submitted job 59721024: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
Submitted job 59721025: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
Submitted job 59721026: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
Submitted job 59721028: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
Submitted job 59721029: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
Submitted job 59721031: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%

Submitted: 15

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-13 08:22 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage status
Result: checked

Jobs from this folder: 15
  pending: 7
  running: 8

All my jobs in the queue: 16
  pending: 8
  running: 8
  free slots under limit 15: 0

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC: 15
  running or pending: 15

======================================================================
2026-10-13 08:22 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 15 folders

running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
running or pending | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%

======================================================================
2026-10-13 11:12 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 15
  pending: 1
  running: 14
  free slots under limit 15: 0

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS: 15
  crashed after reaching accuracy: 13
  not submitted: 2

======================================================================
2026-10-13 11:13 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 15 folders

not submitted | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+0%
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+1%
    slurm-59707139.out: [2026-10-13T04:29:48.750] error: Detected 1 oom_kill event in StepId=59707139.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+2%
    slurm-59707140.out: [2026-10-13T07:16:58.503] error: Detected 1 oom_kill event in StepId=59707140.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_-1%
    slurm-59707141.out: [2026-10-13T05:52:21.255] error: Detected 1 oom_kill event in StepId=59707141.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_-2%
    slurm-59707142.out: [2026-10-13T06:47:51.706] error: Detected 1 oom_kill event in StepId=59707142.0. Some of the step tasks have been OOM Killed.
not submitted | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+0%
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+1%
    slurm-59707144.out: [2026-10-13T06:34:11.598] error: Detected 1 oom_kill event in StepId=59707144.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+2%
    slurm-59707145.out: [2026-10-13T10:00:09.884] error: Detected 2 oom_kill events in StepId=59707145.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_-1%
    slurm-59707146.out: [2026-10-13T08:05:31.471] error: Detected 1 oom_kill event in StepId=59707146.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_-2%
    slurm-59707147.out: [2026-10-13T11:06:24.779] error: Detected 1 oom_kill event in StepId=59707147.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+0%
    slurm-59707148.out: [2026-10-13T02:11:52.405] error: Detected 1 oom_kill event in StepId=59707148.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+1%
    slurm-59707149.out: [2026-10-13T07:09:30.006] error: Detected 1 oom_kill event in StepId=59707149.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_+2%
    slurm-59707150.out: [2026-10-13T11:55:14.353] error: Detected 1 oom_kill event in StepId=59707150.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_-1%
    slurm-59707151.out: [2026-10-13T09:30:21.229] error: Detected 1 oom_kill event in StepId=59707151.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C44/strain_-2%
    slurm-59707152.out: [2026-10-13T12:21:29.222] error: Detected 1 oom_kill event in StepId=59707152.0. Some of the step tasks have been OOM Killed.

======================================================================
2026-10-13 11:13 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS
$ vtriage list not submitted
Result: 2 folders

not submitted | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_I/strain_+0%
not submitted | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/1-SQS/strain_calcs/C11_C12_II/strain_+0%

======================================================================
2026-10-13 15:48 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 10
  pending: 1
  running: 9
  free slots under limit 15: 5

Folders under /pscratch/sd/g/garora/vt_agent1: 10
  not submitted: 10

======================================================================
2026-10-13 15:59 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 10
  pending: 1
  running: 9
  free slots under limit 15: 5

Folders under /pscratch/sd/g/garora/vt_agent1: 10
  not submitted: 10

======================================================================
2026-10-13 16:02 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage schedule --help
Result: finished

usage: schedule.py [-h] [--root ROOT] [--every EVERY] [--path PATH [PATH ...]]
                   [--batch BATCH] [--queue-limit QUEUE_LIMIT]
                   [--agent {off,ask,auto}]
                   {plan,confirm,remove}

Put the auto agent on scrontab or take it off.

positional arguments:
  {plan,confirm,remove}
                        plan, confirm, or remove

optional arguments:
  -h, --help            show this help message and exit
  --root ROOT           campaign root, default is this folder
  --every EVERY         time between cycles, such as 20m or 5h
  --path PATH [PATH ...]
                        path patterns such as C11/2, C11/*, or C11/{2..10};
                        quote them in the shell
  --batch BATCH         new jobs per cycle, default AUTO_BATCH
  --queue-limit QUEUE_LIMIT
                        my jobs allowed in the queue, default AUTO_QUEUE_LIMIT
  --agent {off,ask,auto}
                        decision agent for this campaign, default AGENT_MODE

======================================================================
2026-10-13 16:02 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage schedule --every 10m --batch 10 --agent ask
Result: finished

Schedule plan for /pscratch/sd/g/garora/vt_agent1
  folders: 10, not submitted: 10, in queue: 0
  every 10m: */10 * * * * (times are UTC)
  new jobs per cycle: 10, queue limit: 30
  path patterns: none, every folder
  decision agent: ask
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_agent1
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/vt_agent1/auto_cron.log
  #SCRON --open-mode=append
  */10 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_agent1 --batch 10 --agent ask

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/vt_agent1/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/vt_agent1

======================================================================
2026-10-13 16:04 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage auto submit
Result: up to 10 jobs

2026-10-13 16:03 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 10
  /pscratch/sd/g/garora/vt_agent1/C11/1
  /pscratch/sd/g/garora/vt_agent1/C11/2
  /pscratch/sd/g/garora/vt_agent1/C11/3
  /pscratch/sd/g/garora/vt_agent1/C11/4
  /pscratch/sd/g/garora/vt_agent1/C11/5
  /pscratch/sd/g/garora/vt_agent1/C11/6
  /pscratch/sd/g/garora/vt_agent1/C12/1
  /pscratch/sd/g/garora/vt_agent1/C12/2
  /pscratch/sd/g/garora/vt_agent1/C44/x
  /pscratch/sd/g/garora/vt_agent1/C44/y
Confirmed by --yes.
Submitted job 59749585: /pscratch/sd/g/garora/vt_agent1/C11/1
Submitted job 59749589: /pscratch/sd/g/garora/vt_agent1/C11/2
Submitted job 59749592: /pscratch/sd/g/garora/vt_agent1/C11/3
Submitted job 59749595: /pscratch/sd/g/garora/vt_agent1/C11/4
Submitted job 59749598: /pscratch/sd/g/garora/vt_agent1/C11/5
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C11/6
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C12/1
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C12/2
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C44/x
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C44/y
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)

Submitted: 5

======================================================================
2026-10-13 16:04 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage confirm --root /pscratch/sd/g/garora/vt_agent1
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_agent1
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto
  #SCRON -o /pscratch/sd/g/garora/vt_agent1/auto_cron.log
  #SCRON --open-mode=append
  */10 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_agent1 --batch 10 --agent ask
Old table saved in /pscratch/sd/g/garora/vt_agent1/scrontab_backup_20261013_160344.txt

Running the first cycle now.
2026-10-13 16:03 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 10
  /pscratch/sd/g/garora/vt_agent1/C11/1
  /pscratch/sd/g/garora/vt_agent1/C11/2
  /pscratch/sd/g/garora/vt_agent1/C11/3
  /pscratch/sd/g/garora/vt_agent1/C11/4
  /pscratch/sd/g/garora/vt_agent1/C11/5
  /pscratch/sd/g/garora/vt_agent1/C11/6
  /pscratch/sd/g/garora/vt_agent1/C12/1
  /pscratch/sd/g/garora/vt_agent1/C12/2
  /pscratch/sd/g/garora/vt_agent1/C44/x
  /pscratch/sd/g/garora/vt_agent1/C44/y
Confirmed by --yes.
Submitted job 59749585: /pscratch/sd/g/garora/vt_agent1/C11/1
Submitted job 59749589: /pscratch/sd/g/garora/vt_agent1/C11/2
Submitted job 59749592: /pscratch/sd/g/garora/vt_agent1/C11/3
Submitted job 59749595: /pscratch/sd/g/garora/vt_agent1/C11/4
Submitted job 59749598: /pscratch/sd/g/garora/vt_agent1/C11/5
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C11/6
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C12/1
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C12/2
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C44/x
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)
sbatch failed in /pscratch/sd/g/garora/vt_agent1/C44/y
  sbatch: error: QOSMaxSubmitJobPerUserLimit
sbatch: error: Batch job submission failed: Job violates accounting/QOS policy (job submit limit, user's size and/or time limits)

Submitted: 5

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/vt_agent1/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-13 17:00 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 11
  pending: 2
  running: 9
  free slots under limit 15: 4

Folders under /pscratch/sd/g/garora/vt_agent1: 10
  converged: 5
  not submitted: 5

======================================================================
2026-10-13 17:13 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage unschedule
Result: finished

Schedule: entry removed from scrontab. Old table saved in /pscratch/sd/g/garora/vt_agent1/scrontab_backup_20261013_171330.txt

======================================================================
2026-10-13 17:15 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage schedule --every 10m --batch 5 --agent ask
Result: finished

Schedule plan for /pscratch/sd/g/garora/vt_agent1
  folders: 10, not submitted: 5, in queue: 0
  every 10m: */10 * * * * (times are UTC)
  new jobs per cycle: 5, queue limit: 30
  path patterns: none, every folder
  decision agent: ask
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_agent1
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_vt_agent1_ab52a8
  #SCRON -o /pscratch/sd/g/garora/vt_agent1/auto_cron.log
  #SCRON --open-mode=append
  */10 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_agent1 --batch 5 --agent ask

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/vt_agent1/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/vt_agent1

======================================================================
2026-10-13 17:16 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage auto submit
Result: up to 5 jobs

2026-10-13 17:16 folders: 10, not submitted: 5, in queue: 0

Folders to submit: 5
  /pscratch/sd/g/garora/vt_agent1/C11/6
  /pscratch/sd/g/garora/vt_agent1/C12/1
  /pscratch/sd/g/garora/vt_agent1/C12/2
  /pscratch/sd/g/garora/vt_agent1/C44/x
  /pscratch/sd/g/garora/vt_agent1/C44/y
Confirmed by --yes.
Submitted job 59752902: /pscratch/sd/g/garora/vt_agent1/C11/6
Submitted job 59752903: /pscratch/sd/g/garora/vt_agent1/C12/1
Submitted job 59752904: /pscratch/sd/g/garora/vt_agent1/C12/2
Submitted job 59752905: /pscratch/sd/g/garora/vt_agent1/C44/x
Submitted job 59752906: /pscratch/sd/g/garora/vt_agent1/C44/y

Submitted: 5

======================================================================
2026-10-13 17:16 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage confirm
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_agent1
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_vt_agent1_ab52a8
  #SCRON -o /pscratch/sd/g/garora/vt_agent1/auto_cron.log
  #SCRON --open-mode=append
  */10 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_agent1 --batch 5 --agent ask
Old table saved in /pscratch/sd/g/garora/vt_agent1/scrontab_backup_20261013_171636.txt

Running the first cycle now.
2026-10-13 17:16 folders: 10, not submitted: 5, in queue: 0

Folders to submit: 5
  /pscratch/sd/g/garora/vt_agent1/C11/6
  /pscratch/sd/g/garora/vt_agent1/C12/1
  /pscratch/sd/g/garora/vt_agent1/C12/2
  /pscratch/sd/g/garora/vt_agent1/C44/x
  /pscratch/sd/g/garora/vt_agent1/C44/y
Confirmed by --yes.
Submitted job 59752902: /pscratch/sd/g/garora/vt_agent1/C11/6
Submitted job 59752903: /pscratch/sd/g/garora/vt_agent1/C12/1
Submitted job 59752904: /pscratch/sd/g/garora/vt_agent1/C12/2
Submitted job 59752905: /pscratch/sd/g/garora/vt_agent1/C44/x
Submitted job 59752906: /pscratch/sd/g/garora/vt_agent1/C44/y

Submitted: 5

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/vt_agent1/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-13 17:20 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage agent cycle
Result: decisions made

vtriage agent, 2026-10-13 17:20
Root: /pscratch/sd/g/garora/vt_agent1
Mode: ask. LLM cost this cycle: 0.0089 USD. Campaign total: 0.0089 of 1.00 USD.

Waiting for you (2):
  C12/1: LLM: Only one ionic step (NSW=1) finished with energy change 0.000 eV and max force 0.0000 eV/A, so there is no trend showing progress toward EDIFFG; stress is 485.86 kB.
  C12/2: LLM: Only one ionic step (NSW=1) finished with energy change 0.000 eV and max force 0.0000 eV/A, so there is no trend showing progress toward EDIFFG; stress is 485.86 kB.

Email: Submitted batch job 59753044, to gauravarora.1100@gmail.com

======================================================================
2026-10-13 17:20 | perlmutter | /pscratch/sd/g/garora/vt_agent1
$ vtriage auto finish
Result: campaign done

vasp_triage auto agent finished
Date: 2026-10-13 17:20
Root: /pscratch/sd/g/garora/vt_agent1
Path patterns: none, every folder

Folders: 10
  converged: 8
  ionic not converged: 2

Folders that need a look: 2
  ionic not converged | /pscratch/sd/g/garora/vt_agent1/C12/1 | agent: wait, LLM: Only one ionic step (NSW=1) finished with energy change 0.000 eV and max force 0.0000 eV/A, so there is no trend showing progress toward EDIFFG; stress is 485.86 kB.
  ionic not converged | /pscratch/sd/g/garora/vt_agent1/C12/2 | agent: wait, LLM: Only one ionic step (NSW=1) finished with energy change 0.000 eV and max force 0.0000 eV/A, so there is no trend showing progress toward EDIFFG; stress is 485.86 kB.

Agent LLM cost: 0.0089 USD in 1 calls

Email: Submitted batch job 59753047, to gauravarora.1100@gmail.com

======================================================================
2026-10-13 19:54 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage edit --status not submitted --path C12/* --set NSW=2 --set EDIFF=1E-07 --set EDIFFG=1E-05
Result: finished

Path filter kept 2 of 10 folders.

/pscratch/sd/g/garora/vt_agent2/C12/1
  EDIFF: 1E-05 -> 1E-07
  EDIFFG: -1E-03 -> 1E-05
  NSW: 1 -> 2

/pscratch/sd/g/garora/vt_agent2/C12/2
  EDIFF: 1E-05 -> 1E-07
  EDIFFG: -1E-03 -> 1E-05
  NSW: 1 -> 2

Folders to change: 2
Type yes to save each run and apply the changes: Cancelled. No files changed.

======================================================================
2026-10-13 19:54 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage edit --status not submitted --path C12/* --set NSW=2 --set EDIFF=1E-07 --set EDIFFG=1E-05
Result: finished

Path filter kept 2 of 10 folders.

/pscratch/sd/g/garora/vt_agent2/C12/1
  EDIFF: 1E-05 -> 1E-07
  EDIFFG: -1E-03 -> 1E-05
  NSW: 1 -> 2

/pscratch/sd/g/garora/vt_agent2/C12/2
  EDIFF: 1E-05 -> 1E-07
  EDIFFG: -1E-03 -> 1E-05
  NSW: 1 -> 2

Folders to change: 2
Type yes to save each run and apply the changes: Changed: /pscratch/sd/g/garora/vt_agent2/C12/1
Changed: /pscratch/sd/g/garora/vt_agent2/C12/2

======================================================================
2026-10-13 19:54 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage edit --status not submitted --path C44/x --set NELM=10 --set EDIFF=1E-08
Result: finished

Path filter kept 1 of 10 folders.

/pscratch/sd/g/garora/vt_agent2/C44/x
  EDIFF: 1E-05 -> 1E-08
  NELM: 200 -> 10

Folders to change: 1
Type yes to save each run and apply the changes: Changed: /pscratch/sd/g/garora/vt_agent2/C44/x

======================================================================
2026-10-13 19:54 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 10
  pending: 1
  running: 9
  free slots under limit 15: 5

Folders under /pscratch/sd/g/garora/vt_agent2: 10
  not submitted: 10

======================================================================
2026-10-13 19:55 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage schedule --every 10m --batch 5 --agent auto
Result: finished

Schedule plan for /pscratch/sd/g/garora/vt_agent2
  folders: 10, not submitted: 10, in queue: 0
  every 10m: */10 * * * * (times are UTC)
  new jobs per cycle: 5, queue limit: 30
  path patterns: none, every folder
  decision agent: auto
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_agent2
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_vt_agent2_c5bd2f
  #SCRON -o /pscratch/sd/g/garora/vt_agent2/auto_cron.log
  #SCRON --open-mode=append
  */10 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_agent2 --batch 5 --agent auto

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/vt_agent2/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/vt_agent2

======================================================================
2026-10-13 19:56 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage auto submit
Result: up to 5 jobs

2026-10-13 19:56 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 5
  /pscratch/sd/g/garora/vt_agent2/C11/1
  /pscratch/sd/g/garora/vt_agent2/C11/2
  /pscratch/sd/g/garora/vt_agent2/C11/3
  /pscratch/sd/g/garora/vt_agent2/C11/4
  /pscratch/sd/g/garora/vt_agent2/C11/5
Not submitted now because of the limits: 5
Confirmed by --yes.
Submitted job 59758616: /pscratch/sd/g/garora/vt_agent2/C11/1
Submitted job 59758617: /pscratch/sd/g/garora/vt_agent2/C11/2
Submitted job 59758620: /pscratch/sd/g/garora/vt_agent2/C11/3
Submitted job 59758621: /pscratch/sd/g/garora/vt_agent2/C11/4
Submitted job 59758623: /pscratch/sd/g/garora/vt_agent2/C11/5

Submitted: 5
Run the same command again later for the next batch.

======================================================================
2026-10-13 19:56 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage confirm
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/vt_agent2
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_vt_agent2_c5bd2f
  #SCRON -o /pscratch/sd/g/garora/vt_agent2/auto_cron.log
  #SCRON --open-mode=append
  */10 * * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/vt_agent2 --batch 5 --agent auto
Old table saved in /pscratch/sd/g/garora/vt_agent2/scrontab_backup_20261013_195609.txt

Running the first cycle now.
2026-10-13 19:56 folders: 10, not submitted: 10, in queue: 0

Folders to submit: 5
  /pscratch/sd/g/garora/vt_agent2/C11/1
  /pscratch/sd/g/garora/vt_agent2/C11/2
  /pscratch/sd/g/garora/vt_agent2/C11/3
  /pscratch/sd/g/garora/vt_agent2/C11/4
  /pscratch/sd/g/garora/vt_agent2/C11/5
Not submitted now because of the limits: 5
Confirmed by --yes.
Submitted job 59758616: /pscratch/sd/g/garora/vt_agent2/C11/1
Submitted job 59758617: /pscratch/sd/g/garora/vt_agent2/C11/2
Submitted job 59758620: /pscratch/sd/g/garora/vt_agent2/C11/3
Submitted job 59758621: /pscratch/sd/g/garora/vt_agent2/C11/4
Submitted job 59758623: /pscratch/sd/g/garora/vt_agent2/C11/5

Submitted: 5
Run the same command again later for the next batch.

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/vt_agent2/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-13 20:01 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage auto submit
Result: up to 5 jobs

2026-10-13 20:00 folders: 10, not submitted: 5, in queue: 0

Folders to submit: 5
  /pscratch/sd/g/garora/vt_agent2/C11/6
  /pscratch/sd/g/garora/vt_agent2/C12/1
  /pscratch/sd/g/garora/vt_agent2/C12/2
  /pscratch/sd/g/garora/vt_agent2/C44/x
  /pscratch/sd/g/garora/vt_agent2/C44/y
Confirmed by --yes.
Submitted job 59758762: /pscratch/sd/g/garora/vt_agent2/C11/6
Submitted job 59758765: /pscratch/sd/g/garora/vt_agent2/C12/1
Submitted job 59758766: /pscratch/sd/g/garora/vt_agent2/C12/2
Submitted job 59758768: /pscratch/sd/g/garora/vt_agent2/C44/x
Submitted job 59758770: /pscratch/sd/g/garora/vt_agent2/C44/y

Submitted: 5

======================================================================
2026-10-13 20:10 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage agent cycle
Result: decisions made

vtriage agent, 2026-10-13 20:10
Root: /pscratch/sd/g/garora/vt_agent2
Mode: auto. LLM cost this cycle: 0.0111 USD. Campaign total: 0.0111 of 1.00 USD.

Waiting for you (3):
  C12/1: LLM: Energy jumped from -33.11 to -6.26 eV (+26.85 eV) over 2 steps with stress 12860 kB and max force 0.0000, so the relaxation is diverging, not progressing.
  C12/2: LLM: Energy rose by 26.85 eV from -33.11 to -6.26 eV, stress is 12860 kB and forces read 0.0000, so this is not steady downward progress.
  C44/x: LLM: dE did not fall steadily: it rose to +2.31e-01 at step 6 after reaching -6.87e-04, then fell again to -1.96e-05 against EDIFF 1E-08, which looks unstable.

Email: Submitted batch job 59759045, to gauravarora.1100@gmail.com

======================================================================
2026-10-13 20:10 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage auto finish
Result: campaign done

vasp_triage auto agent finished
Date: 2026-10-13 20:10
Root: /pscratch/sd/g/garora/vt_agent2
Path patterns: none, every folder

Folders: 10
  converged: 7
  SCF not converged: 1
  ionic not converged: 2

Folders that need a look: 3
  ionic not converged | /pscratch/sd/g/garora/vt_agent2/C12/1 | agent: wait, LLM: Energy jumped from -33.11 to -6.26 eV (+26.85 eV) over 2 steps with stress 12860 kB and max force 0.0000, so the relaxation is diverging, not progressing.
  ionic not converged | /pscratch/sd/g/garora/vt_agent2/C12/2 | agent: wait, LLM: Energy rose by 26.85 eV from -33.11 to -6.26 eV, stress is 12860 kB and forces read 0.0000, so this is not steady downward progress.
  SCF not converged | /pscratch/sd/g/garora/vt_agent2/C44/x | last SCF hit NELM | agent: wait, LLM: dE did not fall steadily: it rose to +2.31e-01 at step 6 after reaching -6.87e-04, then fell again to -1.96e-05 against EDIFF 1E-08, which looks unstable.

Agent LLM cost: 0.0111 USD in 1 calls

Email: Submitted batch job 59759047, to gauravarora.1100@gmail.com

======================================================================
2026-10-14 06:07 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage auto finish
Result: campaign done

vasp_triage auto agent finished
Date: 2026-10-14 06:07
Root: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
Path patterns: none, every folder

Folders: 15
  crashed after reaching accuracy: 8
  crashed: 7

Folders that need a look: 15
  crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0% | walltime
  crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1% | out of memory
  crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2% | walltime
  crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1% | out of memory
  crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2% | walltime
  crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0% | out of memory
  crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1% | out of memory
  crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2% | walltime
  crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1% | out of memory
  crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2% | walltime
  crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0% | out of memory
  crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1% | out of memory
  crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2% | walltime
  crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1% | out of memory
  crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2% | walltime

Email: Submitted batch job 59770417, to gauravarora.1100@gmail.com

======================================================================
2026-10-14 10:27 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage agent cycle
Result: decisions made

vtriage agent, 2026-10-14 10:27
Root: /pscratch/sd/g/garora/vt_agent2
Mode: auto. LLM cost this cycle: 0.0110 USD. Campaign total: 0.0110 of 1.50 USD.

NELM raised and rerun (1):
  C44/x: NELM 10 -> 40, rerun, job 59778083. LLM: After the DAV to RMM switch, dE fell from 4.8e-02 (step 7) to 1.96e-05 (step 10), roughly 3-5x per step, so about 6 more steps reach 1e-8; NELM 40 gives margin.

Email: Submitted batch job 59778085, to gauravarora.1100@gmail.com

======================================================================
2026-10-14 10:37 | perlmutter | /pscratch/sd/g/garora/vt_agent2
$ vtriage auto finish
Result: campaign done

vasp_triage auto agent finished
Date: 2026-10-14 10:37
Root: /pscratch/sd/g/garora/vt_agent2
Path patterns: C44/x

Folders: 1
  converged: 1

Folders that need a look: 0

Agent LLM cost: 0.0110 USD in 1 calls

Email: Submitted batch job 59778414, to gauravarora.1100@gmail.com

======================================================================
2026-10-14 12:01 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage schedule
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  folders: 50, not submitted: 50, in queue: 0
  every 5h: 7 */5 * * * (times are UTC)
  Note: 5 does not divide 24, so the gap across midnight UTC is shorter.
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  decision agent: off, from AGENT_MODE at each cycle
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

======================================================================
2026-10-14 12:03 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 15: 15

Folders under /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training: 50
  not submitted: 50

======================================================================
2026-10-14 12:03 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage schedule
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  folders: 50, not submitted: 50, in queue: 0
  every 5h: 7 */5 * * * (times are UTC)
  Note: 5 does not divide 24, so the gap across midnight UTC is shorter.
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  decision agent: off, from AGENT_MODE at each cycle
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

======================================================================
2026-10-14 12:13 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage schedule --every 3h --batch 20 --agent auto
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  folders: 50, not submitted: 50, in queue: 0
  every 3h: 7 */3 * * * (times are UTC)
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  decision agent: auto
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training --batch 20 --agent auto

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

======================================================================
2026-10-14 12:16 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage schedule --every 3h --batch 20 --agent auto
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  folders: 50, not submitted: 50, in queue: 0
  every 3h: 7 */3 * * * (times are UTC)
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  decision agent: auto
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training --batch 20 --agent auto

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

======================================================================
2026-10-14 12:18 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 20 jobs

2026-10-14 12:18 folders: 50, not submitted: 50, in queue: 0

Folders to submit: 20
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
Not submitted now because of the limits: 30
Confirmed by --yes.
Submitted job 59781373: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000
Submitted job 59781375: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
Submitted job 59781376: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
Submitted job 59781378: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003
Submitted job 59781380: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004
Submitted job 59781381: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005
Submitted job 59781383: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
Submitted job 59781384: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007
Submitted job 59781385: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008
Submitted job 59781388: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009
Submitted job 59781390: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010
Submitted job 59781391: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011
Submitted job 59781393: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012
Submitted job 59781394: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013
Submitted job 59781396: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
Submitted job 59781398: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
Submitted job 59781399: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
Submitted job 59781401: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
Submitted job 59781402: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
Submitted job 59781404: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019

Submitted: 20
Run the same command again later for the next batch.

======================================================================
2026-10-14 12:18 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training --batch 20 --agent auto
Old table saved in /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/scrontab_backup_20261014_121840.txt

Running the first cycle now.
2026-10-14 12:18 folders: 50, not submitted: 50, in queue: 0

Folders to submit: 20
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
Not submitted now because of the limits: 30
Confirmed by --yes.
Submitted job 59781373: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000
Submitted job 59781375: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
Submitted job 59781376: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
Submitted job 59781378: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003
Submitted job 59781380: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004
Submitted job 59781381: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005
Submitted job 59781383: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
Submitted job 59781384: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007
Submitted job 59781385: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008
Submitted job 59781388: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009
Submitted job 59781390: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010
Submitted job 59781391: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011
Submitted job 59781393: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012
Submitted job 59781394: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013
Submitted job 59781396: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
Submitted job 59781398: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
Submitted job 59781399: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
Submitted job 59781401: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
Submitted job 59781402: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
Submitted job 59781404: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019

Submitted: 20
Run the same command again later for the next batch.

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-14 14:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 10 jobs

2026-10-14 14:07 folders: 50, not submitted: 30, in queue: 20

Folders to submit: 10
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029
Not submitted now because of the limits: 20
Confirmed by --yes.
Submitted job 59784424: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
Submitted job 59784426: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
Submitted job 59784427: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
Submitted job 59784428: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
Submitted job 59784429: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
Submitted job 59784430: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
Submitted job 59784431: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
Submitted job 59784432: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
Submitted job 59784433: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
Submitted job 59784435: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029

Submitted: 10
Run the same command again later for the next batch.

======================================================================
2026-10-14 14:43 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training
$ vtriage schedule --every 5h --batch 30 --agent auto
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training
  folders: 51, not submitted: 50, in queue: 0
  every 5h: 7 */5 * * * (times are UTC)
  Note: 5 does not divide 24, so the gap across midnight UTC is shorter.
  new jobs per cycle: 30, queue limit: 30
  path patterns: none, every folder
  decision agent: auto
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_b37805
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training --batch 30 --agent auto

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training

======================================================================
2026-10-14 14:46 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training
$ vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_b37805
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training --batch 30 --agent auto
Old table saved in /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training/scrontab_backup_20261014_144620.txt

Running the first cycle now.
2026-10-14 14:46 folders: 50, not submitted: 50, in queue: 0
Queue full: 30 of 30. Nothing submitted.

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-14 20:43 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage unschedule
Result: finished

Schedule: entry removed from scrontab. Old table saved in /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/scrontab_backup_20261014_204344.txt

======================================================================
2026-10-14 20:43 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training
$ vtriage unschedule
Result: finished

Schedule: entry removed from scrontab. Old table saved in /pscratch/sd/g/garora/Villanova/Mo-based_alloys/2-Mo30/1-DFT_training/scrontab_backup_20261014_204357.txt

======================================================================
2026-10-15 09:41 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage schedule --every 3h --batch 20 --agent auto
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  folders: 50, not submitted: 50, in queue: 0
  every 3h: 7 */3 * * * (times are UTC)
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  decision agent: auto
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training --batch 20 --agent auto

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

======================================================================
2026-10-15 09:56 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage schedule --every 3h --batch 20 --agent auto
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  folders: 50, not submitted: 50, in queue: 0
  every 3h: 7 */3 * * * (times are UTC)
  new jobs per cycle: 20, queue limit: 30
  path patterns: none, every folder
  decision agent: auto
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training --batch 20 --agent auto

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

======================================================================
2026-10-15 09:57 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 20 jobs

2026-10-15 09:57 folders: 50, not submitted: 50, in queue: 0

Folders to submit: 20
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
Not submitted now because of the limits: 30
Confirmed by --yes.
Submitted job 59808927: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000
Submitted job 59808930: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
Submitted job 59808932: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
Submitted job 59808955: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003
Submitted job 59808962: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004
Submitted job 59808963: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005
Submitted job 59808964: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
Submitted job 59808965: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007
Submitted job 59808966: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008
Submitted job 59808967: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009
Submitted job 59808968: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010
Submitted job 59808969: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011
Submitted job 59808970: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012
Submitted job 59808971: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013
Submitted job 59808972: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
Submitted job 59808974: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
Submitted job 59808975: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
Submitted job 59808976: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
Submitted job 59808977: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
Submitted job 59808979: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019

Submitted: 20
Run the same command again later for the next batch.

======================================================================
2026-10-15 09:57 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training --batch 20 --agent auto
Old table saved in /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/scrontab_backup_20261015_095708.txt

Running the first cycle now.
2026-10-15 09:57 folders: 50, not submitted: 50, in queue: 0

Folders to submit: 20
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
Not submitted now because of the limits: 30
Confirmed by --yes.
Submitted job 59808927: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000
Submitted job 59808930: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
Submitted job 59808932: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
Submitted job 59808955: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003
Submitted job 59808962: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004
Submitted job 59808963: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005
Submitted job 59808964: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
Submitted job 59808965: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007
Submitted job 59808966: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008
Submitted job 59808967: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009
Submitted job 59808968: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010
Submitted job 59808969: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011
Submitted job 59808970: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012
Submitted job 59808971: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013
Submitted job 59808972: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
Submitted job 59808974: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
Submitted job 59808975: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
Submitted job 59808976: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
Submitted job 59808977: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
Submitted job 59808979: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019

Submitted: 20
Run the same command again later for the next batch.

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-15 11:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 10 jobs

2026-10-15 11:07 folders: 50, not submitted: 30, in queue: 20

Folders to submit: 10
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029
Not submitted now because of the limits: 20
Confirmed by --yes.
Submitted job 59811240: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
Submitted job 59811241: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
Submitted job 59811242: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
Submitted job 59811243: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
Submitted job 59811244: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
Submitted job 59811245: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
Submitted job 59811247: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
Submitted job 59811248: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
Submitted job 59811249: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
Submitted job 59811251: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029

Submitted: 10
Run the same command again later for the next batch.

======================================================================
2026-10-15 14:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage agent cycle
Result: decisions made

vtriage agent, 2026-10-15 14:07
Root: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
Mode: auto. LLM cost this cycle: 0.0000 USD. Campaign total: 0.0000 of 1.50 USD.

Waiting for you (1):
  str-001: crashed: zbrent

Email: Submitted batch job 59817677, to gauravarora.1100@gmail.com

======================================================================
2026-10-15 14:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 3 jobs

2026-10-15 14:07 folders: 50, not submitted: 20, in queue: 27

Folders to submit: 3
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-030
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-031
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-032
Not submitted now because of the limits: 17
Confirmed by --yes.
Submitted job 59817680: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-030
Submitted job 59817681: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-031
Submitted job 59817682: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-032

Submitted: 3
Run the same command again later for the next batch.

======================================================================
2026-10-15 17:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage agent cycle
Result: decisions made

vtriage agent, 2026-10-15 17:07
Root: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
Mode: auto. LLM cost this cycle: 0.0000 USD. Campaign total: 0.0000 of 1.50 USD.

Waiting for you (1):
  str-006: crashed: zbrent

Email: Submitted batch job 59826668, to gauravarora.1100@gmail.com

======================================================================
2026-10-15 17:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 5 jobs

2026-10-15 17:07 folders: 50, not submitted: 17, in queue: 25

Folders to submit: 5
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-033
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-034
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-035
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-036
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-037
Not submitted now because of the limits: 12
Confirmed by --yes.
Submitted job 59826671: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-033
Submitted job 59826676: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-034
Submitted job 59826678: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-035
Submitted job 59826679: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-036
Submitted job 59826681: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-037

Submitted: 5
Run the same command again later for the next batch.

======================================================================
2026-10-15 20:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage agent cycle
Result: decisions made

vtriage agent, 2026-10-15 20:07
Root: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
Mode: auto. LLM cost this cycle: 0.0108 USD. Campaign total: 0.0108 of 1.50 USD.

Waiting for you (2):
  str-002: crashed: zbrent
  str-010: LLM: Energy has flattened near -1705.561 eV (changes ≤1e-4 recently, one rise of +6e-4) while max force fluctuates 0.014-0.042, not steadily falling toward the 0.01 limit.

Email: Submitted batch job 59832752, to gauravarora.1100@gmail.com

======================================================================
2026-10-15 20:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 4 jobs

2026-10-15 20:07 folders: 50, not submitted: 12, in queue: 26

Folders to submit: 4
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-038
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-039
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-040
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-041
Not submitted now because of the limits: 8
Confirmed by --yes.
Submitted job 59832754: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-038
Submitted job 59832755: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-039
Submitted job 59832757: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-040
Submitted job 59832759: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-041

Submitted: 4
Run the same command again later for the next batch.

======================================================================
2026-10-16 05:07 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 1 jobs

2026-10-16 05:07 folders: 50, not submitted: 8, in queue: 29

Folders to submit: 1
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-042
Not submitted now because of the limits: 7
Confirmed by --yes.
Submitted job 59846951: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-042

Submitted: 1
Run the same command again later for the next batch.

======================================================================
2026-10-16 07:40 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 50 folders

converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-000 | -1708.39491847 eV
    slurm-59808927.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     58
crashed | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-001
    slurm-59808930.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 0.8881 eV/A, max stress 75.37 kB (limit 1.0 kB), last ionic dE 5.13e-01 eV, force limit 0.01 eV/A: criteria not met
crashed | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-002
    slurm-59808932.out: ZBRENT: fatal error in bracketing
    last SCF hit NELM
    max force 1.3629 eV/A, max stress 70.30 kB (limit 1.0 kB), last ionic dE 6.92e+01 eV, force limit 0.01 eV/A: criteria not met
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-003 | -1709.13253273 eV
    slurm-59808955.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     34
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-004 | -1714.68851728 eV
    slurm-59808962.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-005 | -1717.20083513 eV
    slurm-59808963.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     50
crashed | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-006
    slurm-59808964.out: ZBRENT: fatal error in bracketing
    max force 0.0724 eV/A, max stress 0.06 kB (limit 1.0 kB), last ionic dE 1.20e-03 eV, force limit 0.01 eV/A: criteria not met
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-007 | -1708.55168419 eV
    slurm-59808965.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     32
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-008 | -1704.55455042 eV
    slurm-59808966.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   6  3     35
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-009 | -1709.98959376 eV
    slurm-59808967.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     48
ionic not converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-010 | -1705.59888678 eV
    slurm-59808968.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     53
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-011 | -1708.96493868 eV
    slurm-59808969.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     42
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-012 | -1709.66145664 eV
    slurm-59808970.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     52
converged | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-013 | -1708.46253298 eV
    slurm-59808971.out: WARNING in EDDRMM: call to ZHEGV failed, returncode =   8  4     36
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-030
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-031
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-032
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-033
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-034
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-035
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-036
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-037
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-038
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-039
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-040
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-041
running or pending | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-042
not submitted | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-043
not submitted | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-044
not submitted | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-045
not submitted | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-046
not submitted | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-047
not submitted | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-048
not submitted | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-049

======================================================================
2026-10-16 07:42 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage unschedule
Result: finished

Schedule: entry removed from scrontab. Old table saved in /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/scrontab_backup_20261016_074230.txt

======================================================================
2026-10-16 07:44 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage schedule --every 5h --batch 30 --agent auto
Result: finished

Schedule plan for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  folders: 50, not submitted: 36, in queue: 0
  every 5h: 7 */5 * * * (times are UTC)
  Note: 5 does not divide 24, so the gap across midnight UTC is shorter.
  new jobs per cycle: 30, queue limit: 30
  path patterns: none, every folder
  decision agent: auto
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training --batch 30 --agent auto

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training

======================================================================
2026-10-16 07:45 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage auto submit
Result: up to 30 jobs

2026-10-16 07:44 folders: 50, not submitted: 36, in queue: 0

Folders to submit: 30
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-030
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-031
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-032
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-033
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-034
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-035
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-036
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-037
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-038
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-039
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-040
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-041
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-042
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-043
Not submitted now because of the limits: 6
Confirmed by --yes.
Submitted job 59852428: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
Submitted job 59852433: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
Submitted job 59852436: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
Submitted job 59852439: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
Submitted job 59852442: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
Submitted job 59852445: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
Submitted job 59852447: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
Submitted job 59852449: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
Submitted job 59852451: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
Submitted job 59852453: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
Submitted job 59852455: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
Submitted job 59852458: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
Submitted job 59852460: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
Submitted job 59852463: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
Submitted job 59852465: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
Submitted job 59852466: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029
Submitted job 59852468: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-030
Submitted job 59852469: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-031
Submitted job 59852470: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-032
Submitted job 59852472: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-033
Submitted job 59852473: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-034
Submitted job 59852474: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-035
Submitted job 59852475: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-036
Submitted job 59852476: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-037
Submitted job 59852477: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-038
Submitted job 59852478: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-039
Submitted job 59852480: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-040
Submitted job 59852481: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-041
Submitted job 59852483: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-042
Submitted job 59852484: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-043

Submitted: 30
Run the same command again later for the next batch.

======================================================================
2026-10-16 07:45 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage confirm --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_1-DFT_training_924f65
  #SCRON -o /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
  #SCRON --open-mode=append
  7 */5 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training --batch 30 --agent auto
Old table saved in /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/scrontab_backup_20261016_074444.txt

Running the first cycle now.
2026-10-16 07:44 folders: 50, not submitted: 36, in queue: 0

Folders to submit: 30
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-030
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-031
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-032
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-033
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-034
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-035
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-036
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-037
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-038
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-039
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-040
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-041
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-042
  /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-043
Not submitted now because of the limits: 6
Confirmed by --yes.
Submitted job 59852428: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-014
Submitted job 59852433: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-015
Submitted job 59852436: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-016
Submitted job 59852439: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-017
Submitted job 59852442: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-018
Submitted job 59852445: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-019
Submitted job 59852447: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-020
Submitted job 59852449: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-021
Submitted job 59852451: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-022
Submitted job 59852453: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-023
Submitted job 59852455: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-024
Submitted job 59852458: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-025
Submitted job 59852460: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-026
Submitted job 59852463: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-027
Submitted job 59852465: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-028
Submitted job 59852466: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-029
Submitted job 59852468: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-030
Submitted job 59852469: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-031
Submitted job 59852470: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-032
Submitted job 59852472: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-033
Submitted job 59852473: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-034
Submitted job 59852474: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-035
Submitted job 59852475: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-036
Submitted job 59852476: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-037
Submitted job 59852477: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-038
Submitted job 59852478: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-039
Submitted job 59852480: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-040
Submitted job 59852481: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-041
Submitted job 59852483: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-042
Submitted job 59852484: /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/str-043

Submitted: 30
Run the same command again later for the next batch.

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-16 13:02 | perlmutter | /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training
$ vtriage unschedule
Result: finished

Schedule: entry removed from scrontab. Old table saved in /pscratch/sd/g/garora/Villanova/Mo-based_alloys/1-Mo28/1-DFT_training/scrontab_backup_20261016_130229.txt

======================================================================
2026-10-16 14:20 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 27
  pending: 26
  running: 1
  free slots under limit 15: 0

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 8
  crashed: 7

======================================================================
2026-10-16 14:20 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 15 folders

crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
    slurm-59721012.out: [2026-10-13T17:42:45.080] error: *** STEP 59721012.0 ON nid004430 CANCELLED AT 2026-10-13T17:42:45 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
    slurm-59721013.out: [2026-10-13T16:35:02.974] error: Detected 1 oom_kill event in StepId=59721013.0. Some of the step tasks have been OOM Killed.
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
    slurm-59721015.out: [2026-10-13T19:36:08.953] error: *** JOB 59721015 ON nid004298 CANCELLED AT 2026-10-13T19:36:08 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
    slurm-59721017.out: [2026-10-13T16:44:59.007] error: Detected 1 oom_kill event in StepId=59721017.0. Some of the step tasks have been OOM Killed.
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
    slurm-59721018.out: [2026-10-14T00:46:15.815] error: *** STEP 59721018.0 ON nid005385 CANCELLED AT 2026-10-14T00:46:15 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
    slurm-59721019.out: [2026-10-13T14:02:30.576] error: Detected 1 oom_kill event in StepId=59721019.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
    slurm-59721020.out: [2026-10-14T01:41:19.111] error: Detected 1 oom_kill event in StepId=59721020.0. Some of the step tasks have been OOM Killed.
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
    slurm-59721021.out: [2026-10-14T04:57:06.538] error: *** STEP 59721021.0 ON nid004175 CANCELLED AT 2026-10-14T04:57:06 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
    slurm-59721022.out: [2026-10-14T02:57:06.930] error: Detected 2 oom_kill events in StepId=59721022.0. Some of the step tasks have been OOM Killed.
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
    slurm-59721024.out: [2026-10-14T06:28:12.928] error: *** STEP 59721024.0 ON nid004970 CANCELLED AT 2026-10-14T06:28:12 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
    slurm-59721025.out: [2026-10-13T19:22:27.184] error: Detected 1 oom_kill event in StepId=59721025.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
    slurm-59721026.out: [2026-10-14T02:42:26.116] error: Detected 1 oom_kill event in StepId=59721026.0. Some of the step tasks have been OOM Killed.
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
    slurm-59721028.out: [2026-10-14T07:01:14.485] error: *** STEP 59721028.0 ON nid004247 CANCELLED AT 2026-10-14T07:01:14 DUE TO TIME LIMIT ***
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
    slurm-59721029.out: [2026-10-14T06:23:46.384] error: Detected 2 oom_kill events in StepId=59721029.0. Some of the step tasks have been OOM Killed.
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%
    slurm-59721031.out: [2026-10-14T08:12:45.325] error: *** STEP 59721031.0 ON nid004270 CANCELLED AT 2026-10-14T08:12:45 DUE TO TIME LIMIT ***

======================================================================
2026-10-16 14:20 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage list crashed
Result: 7 folders

crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
    slurm-59721012.out: [2026-10-13T17:42:45.080] error: *** STEP 59721012.0 ON nid004430 CANCELLED AT 2026-10-13T17:42:45 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
    slurm-59721015.out: [2026-10-13T19:36:08.953] error: *** JOB 59721015 ON nid004298 CANCELLED AT 2026-10-13T19:36:08 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
    slurm-59721018.out: [2026-10-14T00:46:15.815] error: *** STEP 59721018.0 ON nid005385 CANCELLED AT 2026-10-14T00:46:15 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
    slurm-59721021.out: [2026-10-14T04:57:06.538] error: *** STEP 59721021.0 ON nid004175 CANCELLED AT 2026-10-14T04:57:06 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
    slurm-59721024.out: [2026-10-14T06:28:12.928] error: *** STEP 59721024.0 ON nid004970 CANCELLED AT 2026-10-14T06:28:12 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
    slurm-59721028.out: [2026-10-14T07:01:14.485] error: *** STEP 59721028.0 ON nid004247 CANCELLED AT 2026-10-14T07:01:14 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%
    slurm-59721031.out: [2026-10-14T08:12:45.325] error: *** STEP 59721031.0 ON nid004270 CANCELLED AT 2026-10-14T08:12:45 DUE TO TIME LIMIT ***

======================================================================
2026-10-16 14:22 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
Result: finished

Jobs in queue: 27 of limit 15
Queue is full. Nothing submitted.

======================================================================
2026-10-16 14:23 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage submit --status incomplete --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
Result: finished

Jobs in queue: 1 of limit 15
No folders selected.

======================================================================
2026-10-16 14:23 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage submit --status incomplete --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
Result: finished

Jobs in queue: 1 of limit 15
No folders selected.

======================================================================
2026-10-16 14:27 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
Result: finished

Jobs in queue: 1 of limit 15

Folders to submit: 7
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
Submitted job 59864283: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
Submitted job 59864285: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
Submitted job 59864286: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
Submitted job 59864288: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
Submitted job 59864289: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
Submitted job 59864292: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
Archived as run 1: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%
Submitted job 59864295: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%

Submitted: 7

======================================================================
2026-10-16 15:35 | perlmutter | /pscratch/sd/g/garora/lhs_runs/LHS-20261016-YZ6GG
$ vtriage schedule --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-YZ6GG --every 3h --batch 2
Result: finished

Schedule plan for /pscratch/sd/g/garora/lhs_runs/LHS-20261016-YZ6GG
  folders: 2, not submitted: 2, in queue: 0
  every 3h: 7 */3 * * * (times are UTC)
  new jobs per cycle: 2, queue limit: 30
  path patterns: none, every folder
  decision agent: off, from AGENT_MODE at each cycle
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/lhs_runs/LHS-20261016-YZ6GG
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_LHS-20261016-YZ6GG_138cf3
  #SCRON -o /pscratch/sd/g/garora/lhs_runs/LHS-20261016-YZ6GG/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-YZ6GG --batch 2

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/lhs_runs/LHS-20261016-YZ6GG/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-YZ6GG

======================================================================
2026-10-16 15:37 | perlmutter | /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
$ vtriage schedule --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB --every 3h --batch 2
Result: finished

Schedule plan for /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
  folders: 2, not submitted: 2, in queue: 0
  every 3h: 7 */3 * * * (times are UTC)
  new jobs per cycle: 2, queue limit: 30
  path patterns: none, every folder
  decision agent: off, from AGENT_MODE at each cycle
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_LHS-20261016-V7QCB_f25f32
  #SCRON -o /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB --batch 2

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB

======================================================================
2026-10-16 15:38 | perlmutter | /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
$ vtriage auto submit
Result: up to 2 jobs

2026-10-16 15:38 folders: 2, not submitted: 2, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/str-000
  /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/str-001
Confirmed by --yes.
Submitted job 59867383: /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/str-000
Submitted job 59867384: /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/str-001

Submitted: 2

======================================================================
2026-10-16 15:38 | perlmutter | /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
$ vtriage confirm --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
Result: finished

Installed in the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_LHS-20261016-V7QCB_f25f32
  #SCRON -o /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB --batch 2
Old table saved in /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/scrontab_backup_20261016_153800.txt

Running the first cycle now.
2026-10-16 15:38 folders: 2, not submitted: 2, in queue: 0

Folders to submit: 2
  /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/str-000
  /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/str-001
Confirmed by --yes.
Submitted job 59867383: /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/str-000
Submitted job 59867384: /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/str-001

Submitted: 2

Check with: scrontab -l and squeue -u $USER
Watch with: tail -f /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/auto_cron.log
The entry removes itself after the email is sent.

======================================================================
2026-10-16 15:38 | perlmutter | /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
$ vtriage unschedule --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB
Result: finished

Schedule: entry removed from scrontab. Old table saved in /pscratch/sd/g/garora/lhs_runs/LHS-20261016-V7QCB/scrontab_backup_20261016_153823.txt

======================================================================
2026-10-16 15:56 | perlmutter | /pscratch/sd/g/garora/lhs_runs/LHS-20261016-NQVYZ
$ vtriage schedule --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-NQVYZ --every 3h --batch 2
Result: finished

Schedule plan for /pscratch/sd/g/garora/lhs_runs/LHS-20261016-NQVYZ
  folders: 2, not submitted: 2, in queue: 0
  every 3h: 7 */3 * * * (times are UTC)
  new jobs per cycle: 2, queue limit: 30
  path patterns: none, every folder
  decision agent: off, from AGENT_MODE at each cycle
  email when done: gauravarora.1100@gmail.com

Block to add to the scrontab table:
  # vtriage schedule for /pscratch/sd/g/garora/lhs_runs/LHS-20261016-NQVYZ
  #SCRON -q cron
  #SCRON -A m4349
  #SCRON -t 00:10:00
  #SCRON -J vtriage_auto_LHS-20261016-NQVYZ_2413ad
  #SCRON -o /pscratch/sd/g/garora/lhs_runs/LHS-20261016-NQVYZ/auto_cron.log
  #SCRON --open-mode=append
  7 */3 * * * /global/u1/g/garora/vasp_triage/vtriage auto --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-NQVYZ --batch 2

Nothing installed yet. Plan saved to /pscratch/sd/g/garora/lhs_runs/LHS-20261016-NQVYZ/schedule_plan.json
On confirm, the block is installed and one cycle runs at once.
To confirm, run:
  vtriage confirm --root /pscratch/sd/g/garora/lhs_runs/LHS-20261016-NQVYZ

======================================================================
2026-10-17 07:10 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 15: 15

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/9-W10-2vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 15

======================================================================
2026-10-17 16:56 | perlmutter | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs
$ vtriage status
Result: checked

Jobs from this folder: 2
  running: 2

All my jobs in the queue: 2
  running: 2
  free slots under limit 15: 13

Folders under /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs: 21
  converged: 5
  incomplete: 2
  running or pending: 1
  missing inputs: 13

======================================================================
2026-10-18 08:19 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 15 folders

crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
    slurm-59602234.out: [2026-10-10T03:20:47.574] error: Detected 1 oom_kill event in StepId=59602234.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
    slurm-59602235.out: [2026-10-10T03:30:42.198] error: Detected 1 oom_kill event in StepId=59602235.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
    slurm-59602237.out: [2026-10-10T05:10:24.550] error: Detected 1 oom_kill event in StepId=59602237.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
    slurm-59602241.out: [2026-10-10T06:33:01.254] error: Detected 1 oom_kill event in StepId=59602241.0. Some of the step tasks have been OOM Killed.
    last SCF hit NELM
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
    slurm-59602245.out: [2026-10-10T06:35:01.658] error: Detected 1 oom_kill event in StepId=59602245.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
    slurm-59602246.out: [2026-10-10T08:56:01.758] error: Detected 1 oom_kill event in StepId=59602246.0. Some of the step tasks have been OOM Killed.
    last SCF hit NELM
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
    slurm-59602247.out: [2026-10-10T08:25:38.192] error: Detected 1 oom_kill event in StepId=59602247.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
    slurm-59602249.out: [2026-10-10T08:31:50.321] error: Detected 1 oom_kill event in StepId=59602249.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
    slurm-59602251.out: [2026-10-10T10:24:07.280] error: Detected 2 oom_kill events in StepId=59602251.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
    slurm-59602252.out: [2026-10-10T10:54:41.146] error: Detected 1 oom_kill event in StepId=59602252.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
    slurm-59602253.out: [2026-10-10T14:55:12.602] error: Detected 1 oom_kill event in StepId=59602253.0. Some of the step tasks have been OOM Killed.
    last SCF hit NELM
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
    slurm-59602254.out: [2026-10-10T15:52:04.796] error: Detected 1 oom_kill event in StepId=59602254.0. Some of the step tasks have been OOM Killed.
    last SCF hit NELM
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
    slurm-59602256.out: [2026-10-10T14:48:56.696] error: Detected 1 oom_kill event in StepId=59602256.0. Some of the step tasks have been OOM Killed.
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
    slurm-59602257.out: [2026-10-10T17:39:07.370] error: Detected 1 oom_kill event in StepId=59602257.0. Some of the step tasks have been OOM Killed.
    last SCF hit NELM
crashed after reaching accuracy | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%
    slurm-59602260.out: [2026-10-10T17:01:21.379] error: Detected 1 oom_kill event in StepId=59602260.0. Some of the step tasks have been OOM Killed.

======================================================================
2026-10-18 08:19 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage status /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 1
  running: 1
  free slots under limit 15: 14

Folders under /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC: 15
  crashed after reaching accuracy: 15

Needs a look:
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1% [SCF at NELM]
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1% [SCF at NELM]

======================================================================
2026-10-18 08:21 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage submit --group converged --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
Result: finished

Jobs in queue: 1 of limit 15
No folders selected.

======================================================================
2026-10-18 08:22 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage submit --group converged --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
Result: finished

Jobs in queue: 1 of limit 15
No folders selected.

======================================================================
2026-10-18 08:22 | perlmutter | /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
$ vtriage submit --group almost_converged --root /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC
Result: finished

Jobs in queue: 1 of limit 15
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
Warning: last SCF hit NELM. Fix NELM or ALGO first: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
Warning: last SCF hit NELM. Fix NELM or ALGO first: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
Warning: last SCF hit NELM. Fix NELM or ALGO first: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
Warning: last SCF hit NELM. Fix NELM or ALGO first: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
Warning: last SCF hit NELM. Fix NELM or ALGO first: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
Note: reached required accuracy before the job died. Fix the cause, then this should finish quickly: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-2%

Folders to submit: 14
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%  (CONTCAR to POSCAR)
Not submitted now because of the limits: 1
Type yes to save each run and submit: Archived as run 3: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
Submitted job 59946247: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+0%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
Submitted job 59946248: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+1%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
Submitted job 59946249: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_+2%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
Submitted job 59946251: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-1%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
Submitted job 59946252: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_I/strain_-2%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
Submitted job 59946253: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+0%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
Submitted job 59946255: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+1%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
Submitted job 59946257: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_+2%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
Submitted job 59946258: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-1%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
Submitted job 59946262: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C11_C12_II/strain_-2%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
Submitted job 59946263: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+0%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
Submitted job 59946290: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+1%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
Submitted job 59946293: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_+2%
Archived as run 2: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%
Submitted job 59946301: /pscratch/sd/g/garora/Villanova/11-W_based_HEAs/3-elastic-production/8-W10-1vac/2-elastic/2-MEC/strain_calcs/C44/strain_-1%

Submitted: 14
Run the same command again later for the next batch.

======================================================================
2026-10-20 09:08 | perlmutter | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 15: 15

Folders under /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs: 20
  converged: 10
  incomplete: 3
  missing inputs: 7

======================================================================
2026-10-20 09:09 | perlmutter | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs
$ vtriage list converged
Result: 10 folders

converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-0 | -5522.57116263 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-1 | -5522.05490699 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-11 | -5522.69587535 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-12 | -5521.69865665 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-13 | -5522.05013853 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-14 | -5522.20982638 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-2 | -5522.55783224 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-3 | -5522.22268405 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-4 | -5521.63060792 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-5 | -5522.45569817 eV
    missing: submit_vasp.sh

======================================================================
2026-10-20 09:12 | perlmutter | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 15: 15

Folders under /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs: 20
  converged: 10
  incomplete: 3
  missing inputs: 7

======================================================================
2026-10-20 09:13 | perlmutter | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 20 folders

converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-0 | -5522.57116263 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-1 | -5522.05490699 eV
    missing: submit_vasp.sh
missing inputs | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-10
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-11 | -5522.69587535 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-12 | -5521.69865665 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-13 | -5522.05013853 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-14 | -5522.20982638 eV
    missing: submit_vasp.sh
incomplete | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-15
    missing: submit_vasp.sh
missing inputs | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-16
    missing: submit_vasp.sh
missing inputs | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-17
    missing: submit_vasp.sh
missing inputs | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-18
    missing: submit_vasp.sh
missing inputs | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-19
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-2 | -5522.55783224 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-3 | -5522.22268405 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-4 | -5521.63060792 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-5 | -5522.45569817 eV
    missing: submit_vasp.sh
incomplete | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-6
    missing: submit_vasp.sh
incomplete | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-7
    missing: submit_vasp.sh
missing inputs | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-8
    missing: submit_vasp.sh
missing inputs | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-9
    missing: submit_vasp.sh

======================================================================
2026-10-20 09:13 | perlmutter | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs
$ vtriage list converged
Result: 10 folders

converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-0 | -5522.57116263 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-1 | -5522.05490699 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-11 | -5522.69587535 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-12 | -5521.69865665 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-13 | -5522.05013853 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-14 | -5522.20982638 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-2 | -5522.55783224 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-3 | -5522.22268405 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-4 | -5521.63060792 eV
    missing: submit_vasp.sh
converged | /pscratch/sd/g/garora/Villanova/W10-4vac-ransom_strs/str-5 | -5522.45569817 eV
    missing: submit_vasp.sh

======================================================================
2026-10-22 07:04 | perlmutter | /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 0 of limit 15

Folders to submit: 9
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-10
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-2
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-3
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-4
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-5
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-6
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-7
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-8
  /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-9
Type yes to save each run and submit: Submitted job 60101809: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-10
Submitted job 60101810: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-2
Submitted job 60101811: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-3
Submitted job 60101812: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-4
Submitted job 60101813: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-5
Submitted job 60101814: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-6
Submitted job 60101815: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-7
Submitted job 60101816: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-8
Submitted job 60101817: /pscratch/sd/g/garora/Villanova/W_MECx/W10-DFT_for_MECs/2-MECS_from_6x6x6_mecx/str-9

Submitted: 9

======================================================================
2026-10-22 15:23 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage submit
Result: failed, exit code 1

Error: give exactly one of --status, --group, or --list.

======================================================================
2026-10-22 15:23 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 0 of limit 15

Folders to submit: 10
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_22Oct2026_11-20AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60123713: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best
Submitted job 60123717: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best
Submitted job 60123718: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Submitted job 60123719: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
Submitted job 60123720: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best
Submitted job 60123721: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
Submitted job 60123722: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best
Submitted job 60123723: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_22Oct2026_11-20AM/T_0100K/Best_of_Best
Submitted job 60123725: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best
Submitted job 60123726: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best

Submitted: 10

======================================================================
2026-10-22 17:37 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
Result: finished

Jobs in queue: 0 of limit 15

Folders to submit: 10
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_22Oct2026_11-20AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60129339: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best
Submitted job 60129340: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best
Submitted job 60129341: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Submitted job 60129343: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
Submitted job 60129345: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best
Submitted job 60129346: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
Submitted job 60129349: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best
Submitted job 60129350: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_22Oct2026_11-20AM/T_0100K/Best_of_Best
Submitted job 60129351: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best
Submitted job 60129352: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best

Submitted: 10

======================================================================
2026-10-22 17:39 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 28 of limit 15
Queue is full. Nothing submitted.

======================================================================
2026-10-22 17:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 10 of limit 15

Folders to submit: 5
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_02-44PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_02-47PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_02-50PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_02-54PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_02-57PM/T_0100K/Best_of_Best
Not submitted now because of the limits: 13
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-22 17:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 10 of limit 15

Folders to submit: 5
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best
Not submitted now because of the limits: 4
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-22 17:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 10 of limit 15

Folders to submit: 5
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best
Not submitted now because of the limits: 4
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-22 17:51 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 10 of limit 15

Folders to submit: 5
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best
Not submitted now because of the limits: 4
Type yes to save each run and submit: Submitted job 60129851: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best
Submitted job 60129853: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
Submitted job 60129854: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
Submitted job 60129855: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best
Submitted job 60129859: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best

Submitted: 5
Run the same command again later for the next batch.

======================================================================
2026-10-22 17:53 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 15 of limit 15
Queue is full. Nothing submitted.

======================================================================
2026-10-22 17:54 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 15 of limit 100

Folders to submit: 4
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/6-6Y/MC_Run_22Oct2026_12-02PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/7-7Y/MC_Run_22Oct2026_12-04PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/8-8Y/MC_Run_22Oct2026_12-06PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/9-9Y/MC_Run_22Oct2026_12-07PM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60129946: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/6-6Y/MC_Run_22Oct2026_12-02PM/T_0100K/Best_of_Best
Submitted job 60129947: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/7-7Y/MC_Run_22Oct2026_12-04PM/T_0100K/Best_of_Best
Submitted job 60129948: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/8-8Y/MC_Run_22Oct2026_12-06PM/T_0100K/Best_of_Best
Submitted job 60129949: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/9-9Y/MC_Run_22Oct2026_12-07PM/T_0100K/Best_of_Best

Submitted: 4

======================================================================
2026-10-22 18:15 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 19 of limit 100

Folders to submit: 20
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-27PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-17PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
Not submitted now because of the limits: 7
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-22 18:16 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 19 of limit 100

Folders to submit: 20
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-27PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-17PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
Not submitted now because of the limits: 7
Type yes to save each run and submit: Submitted job 60130645: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
Submitted job 60130647: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
Submitted job 60130650: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Submitted job 60130652: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Submitted job 60130655: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
Submitted job 60130657: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
Submitted job 60130661: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Submitted job 60130663: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best
Submitted job 60130665: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
Submitted job 60130666: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-27PM/T_0100K/Best_of_Best
Submitted job 60130667: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Submitted job 60130669: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Submitted job 60130670: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Submitted job 60130671: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Submitted job 60130672: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
Submitted job 60130675: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-17PM/T_0100K/Best_of_Best
Submitted job 60130676: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Submitted job 60130678: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
Submitted job 60130680: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
Submitted job 60130681: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best

Submitted: 20
Run the same command again later for the next batch.

======================================================================
2026-10-22 18:16 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5 --queue-limit 100
Result: finished

Jobs in queue: 39 of limit 100

Folders to submit: 7
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-54PM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60130697: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
Submitted job 60130699: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
Submitted job 60130700: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
Submitted job 60130701: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
Submitted job 60130702: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
Submitted job 60130703: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
Submitted job 60130704: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-54PM/T_0100K/Best_of_Best

Submitted: 7

======================================================================
2026-10-22 19:31 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 46 of limit 100

Folders to submit: 20
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
Not submitted now because of the limits: 7
Type yes to save each run and submit: Submitted job 60134402: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
Submitted job 60134404: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Submitted job 60134405: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Submitted job 60134406: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Submitted job 60134407: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Submitted job 60134408: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
Submitted job 60134409: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Submitted job 60134410: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best
Submitted job 60134411: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
Submitted job 60134412: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Submitted job 60134413: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Submitted job 60134414: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Submitted job 60134415: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Submitted job 60134416: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Submitted job 60134417: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
Submitted job 60134418: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best
Submitted job 60134419: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Submitted job 60134420: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
Submitted job 60134421: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
Submitted job 60134423: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best

Submitted: 20
Run the same command again later for the next batch.

======================================================================
2026-10-22 19:31 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6 --queue-limit 30
Result: finished

Jobs in queue: 66 of limit 30
Queue is full. Nothing submitted.

======================================================================
2026-10-23 07:22 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 53
  pending: 52
  running: 1
  free slots under limit 100: 47

Folders under /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4: 11
  converged: 7
  crashed: 3
  missing inputs: 1

======================================================================
2026-10-23 07:22 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 11 folders

missing inputs | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
    missing: POSCAR, POTCAR
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best | -5587.76234591 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best | -5587.76229245 eV
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
    slurm-60129341.out: [2026-10-23T04:43:32.194] error: *** STEP 60129341.0 ON nid004723 CANCELLED AT 2026-10-23T04:43:32 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
    slurm-60129343.out: [2026-10-23T04:44:14.496] error: *** STEP 60129343.0 ON nid005273 CANCELLED AT 2026-10-23T04:44:14 DUE TO TIME LIMIT ***
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best | -5597.89158739 eV
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
    slurm-60129346.out: [2026-10-23T05:55:41.901] error: *** STEP 60129346.0 ON nid004975 CANCELLED AT 2026-10-23T05:55:41 DUE TO TASK FAILURE ***
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best | -5594.42438105 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_22Oct2026_11-20AM/T_0100K/Best_of_Best | -5590.47923262 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best | -5590.47930228 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best | -5590.28180853 eV

======================================================================
2026-10-23 07:23 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 53
  pending: 52
  running: 1
  free slots under limit 100: 47

Folders under /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4: 11
  converged: 7
  crashed: 3
  missing inputs: 1

======================================================================
2026-10-23 07:23 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 11 folders

missing inputs | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
    missing: POSCAR, POTCAR
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best | -5587.76234591 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best | -5587.76229245 eV
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
    slurm-60129341.out: [2026-10-23T04:43:32.194] error: *** STEP 60129341.0 ON nid004723 CANCELLED AT 2026-10-23T04:43:32 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
    slurm-60129343.out: [2026-10-23T04:44:14.496] error: *** STEP 60129343.0 ON nid005273 CANCELLED AT 2026-10-23T04:44:14 DUE TO TIME LIMIT ***
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best | -5597.89158739 eV
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
    slurm-60129346.out: [2026-10-23T05:55:41.901] error: *** STEP 60129346.0 ON nid004975 CANCELLED AT 2026-10-23T05:55:41 DUE TO TASK FAILURE ***
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best | -5594.42438105 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_22Oct2026_11-20AM/T_0100K/Best_of_Best | -5590.47923262 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best | -5590.47930228 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best | -5590.28180853 eV

======================================================================
2026-10-23 07:24 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list crashed incomplete
Result: 3 folders

crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
    slurm-60129341.out: [2026-10-23T04:43:32.194] error: *** STEP 60129341.0 ON nid004723 CANCELLED AT 2026-10-23T04:43:32 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
    slurm-60129343.out: [2026-10-23T04:44:14.496] error: *** STEP 60129343.0 ON nid005273 CANCELLED AT 2026-10-23T04:44:14 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
    slurm-60129346.out: [2026-10-23T05:55:41.901] error: *** STEP 60129346.0 ON nid004975 CANCELLED AT 2026-10-23T05:55:41 DUE TO TASK FAILURE ***

======================================================================
2026-10-23 07:25 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage edit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4 --set ALGO=All
Result: finished


/pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

/pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

/pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 3
Type yes to save each run and apply the changes: Archived as run 1: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Changed: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Archived as run 1: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
Changed: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
Archived as run 1: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
Changed: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best

======================================================================
2026-10-23 07:25 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
Result: finished

Jobs in queue: 53 of limit 100
CONTCAR missing or empty, skipped: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best

Folders to submit: 2
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
Type yes to save each run and submit: CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Submitted job 60154390: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Submitted job 60154392: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best

Submitted: 2

======================================================================
2026-10-23 07:27 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage status
Result: checked

Jobs from this folder: 6
  pending: 5
  running: 1

All my jobs in the queue: 56
  pending: 55
  running: 1
  free slots under limit 100: 44

Folders under /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6: 10
  converged: 2
  crashed: 1
  running or pending: 6
  missing inputs: 1

======================================================================
2026-10-23 07:27 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage list crashed
Result: 1 folders

crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
    slurm-60129854.out: [2026-10-23T11:10:58.889] error: *** STEP 60129854.0 ON nid004699 CANCELLED AT 2026-10-23T11:10:58 DUE TO TASK FAILURE ***

======================================================================
2026-10-23 07:28 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage edit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6 --set ALGO=All
Result: finished


/pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 1
Type yes to save each run and apply the changes: Archived as run 1: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
Changed: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best

======================================================================
2026-10-23 07:28 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
Result: finished

Jobs in queue: 56 of limit 100

Folders to submit: 1
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60154456: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-23 11:03 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 3
  pending: 3

All my jobs in the queue: 51
  pending: 48
  running: 3
  free slots under limit 100: 49

Folders under /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4: 10
  converged: 6
  running or pending: 3
  missing inputs: 1

======================================================================
2026-10-23 11:03 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list converged
Result: 6 folders

converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best | -5587.76234591 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best | -5587.76229245 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best | -5597.89158739 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best | -5594.42438105 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best | -5590.47930228 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best | -5590.28180853 eV

======================================================================
2026-10-23 11:07 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage list converged
Result: 6 folders

converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best | -5587.48648865 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best | -5597.89176512 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best | -5595.43980543 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/6-6Y/MC_Run_22Oct2026_12-02PM/T_0100K/Best_of_Best | -5594.21664938 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/8-8Y/MC_Run_22Oct2026_12-06PM/T_0100K/Best_of_Best | -5590.25872811 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/9-9Y/MC_Run_22Oct2026_12-07PM/T_0100K/Best_of_Best | -5589.97591028 eV

======================================================================
2026-10-24 06:02 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 100: 100

Folders under /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4: 10
  converged: 6
  crashed: 3
  missing inputs: 1

======================================================================
2026-10-24 06:02 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 10 folders

missing inputs | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
    missing: POSCAR, POTCAR
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best | -5587.76234591 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best | -5587.76229245 eV
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
    slurm-60154390.out: [2026-10-23T20:47:07.896] error: *** STEP 60154390.0 ON nid005823 CANCELLED AT 2026-10-23T20:47:07 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
    slurm-60154417.out: [2026-10-23T21:33:42.354] error: *** STEP 60154417.0 ON nid005255 CANCELLED AT 2026-10-23T21:33:42 DUE TO TIME LIMIT ***
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best | -5597.89158739 eV
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
    slurm-60154392.out: [2026-10-23T20:47:07.908] error: *** STEP 60154392.0 ON nid006348 CANCELLED AT 2026-10-23T20:47:07 DUE TO TIME LIMIT ***
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best | -5594.42438105 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best | -5590.47930228 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best | -5590.28180853 eV

======================================================================
2026-10-24 06:02 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list SCF not converged ionic not converged
Result: 0 folders

No folder has that status.

======================================================================
2026-10-24 06:02 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list crashed incomplete
Result: 3 folders

crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
    slurm-60154390.out: [2026-10-23T20:47:07.896] error: *** STEP 60154390.0 ON nid005823 CANCELLED AT 2026-10-23T20:47:07 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
    slurm-60154417.out: [2026-10-23T21:33:42.354] error: *** STEP 60154417.0 ON nid005255 CANCELLED AT 2026-10-23T21:33:42 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
    slurm-60154392.out: [2026-10-23T20:47:07.908] error: *** STEP 60154392.0 ON nid006348 CANCELLED AT 2026-10-23T20:47:07 DUE TO TIME LIMIT ***

======================================================================
2026-10-24 06:05 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
Result: finished

Jobs in queue: 0 of limit 100
Warning: same error as previous run (walltime). Change settings first: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best

Folders to submit: 3
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 2: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Submitted job 60204291: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best
Archived as run 2: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
Submitted job 60204292: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best
Archived as run 2: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best
Submitted job 60204294: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4/mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best

Submitted: 3

======================================================================
2026-10-24 06:05 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
Result: checked

Jobs from this folder: 3
  pending: 3

All my jobs in the queue: 3
  pending: 3
  free slots under limit 100: 97

Folders under /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4: 10
  converged: 6
  running or pending: 3
  missing inputs: 1

======================================================================
2026-10-24 06:06 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 3
  pending: 3
  free slots under limit 100: 97

Folders under /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6: 9
  converged: 6
  crashed: 2
  missing inputs: 1

======================================================================
2026-10-24 06:06 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage list crashed incomplete
Result: 2 folders

crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
    slurm-60129853.out: [2026-10-23T11:29:11.701] error: *** STEP 60129853.0 ON nid004376 CANCELLED AT 2026-10-23T11:29:11 DUE TO TIME LIMIT ***
crashed | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
    slurm-60154456.out: [2026-10-23T21:33:42.358] error: *** STEP 60154456.0 ON nid005387 CANCELLED AT 2026-10-23T21:33:42 DUE TO TIME LIMIT ***

======================================================================
2026-10-24 06:08 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
Result: finished

Jobs in queue: 3 of limit 100
CONTCAR missing or empty, skipped: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best

Folders to submit: 1
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-24 06:09 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
Result: finished

Jobs in queue: 3 of limit 100
CONTCAR missing or empty, skipped: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best

Folders to submit: 1
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Cancelled. Nothing submitted.

======================================================================
2026-10-24 06:09 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
Result: finished

Jobs in queue: 3 of limit 100
CONTCAR missing or empty, skipped: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best

Folders to submit: 1
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 2: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
Submitted job 60204409: /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-24 06:18 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed incomplete running or pending not submitted missing inputs
Result: 9 folders

missing inputs | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
    missing: POSCAR, POTCAR
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best | -5587.48648865 eV
running or pending | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
running or pending | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best | -5597.89176512 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best | -5595.43980543 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/6-6Y/MC_Run_22Oct2026_12-02PM/T_0100K/Best_of_Best | -5594.21664938 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/8-8Y/MC_Run_22Oct2026_12-06PM/T_0100K/Best_of_Best | -5590.25872811 eV
converged | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs/9-9Y/MC_Run_22Oct2026_12-07PM/T_0100K/Best_of_Best | -5589.97591028 eV

======================================================================
2026-10-24 06:19 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status incomplete --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
Result: finished

Jobs in queue: 5 of limit 100
No folders selected.

======================================================================
2026-10-24 06:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 5
  running: 5
  free slots under limit 100: 95

Folders under /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5: 28
  converged: 2
  crashed: 13
  SCF diverged: 12
  missing inputs: 1

Needs a look:
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best [SCF diverged]
  /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-24 06:45 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 5
  running: 5
  free slots under limit 100: 95

Folders under .: 28
  crashed: 11
  SCF diverged: 9
  not submitted: 7
  missing inputs: 1

Needs a look:
  mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-24 06:46 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage list crashed
Result: 11 folders

crashed | mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
    slurm-60134402.out: [2026-10-23T20:38:02.819] error: *** JOB 60134402 ON nid005366 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60134405.out: [2026-10-23T20:02:53.595] error: *** STEP 60134405.0 ON nid004904 CANCELLED AT 2026-10-23T20:02:53 DUE TO TASK FAILURE ***
crashed | mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
    slurm-60134408.out: [2026-10-23T20:38:02.820] error: *** STEP 60134408.0 ON nid004515 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best
    slurm-60134410.out: [2026-10-23T20:38:02.818] error: *** STEP 60134410.0 ON nid004562 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
    slurm-60134411.out: [2026-10-23T20:38:02.816] error: *** STEP 60134411.0 ON nid004578 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60134412.out: [2026-10-23T20:38:02.820] error: *** STEP 60134412.0 ON nid005519 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60134414.out: [2026-10-23T20:38:02.822] error: *** STEP 60134414.0 ON nid006521 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best
    slurm-60134418.out: [2026-10-23T20:38:02.825] error: *** STEP 60134418.0 ON nid005178 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
    slurm-60134419.out: [2026-10-23T20:38:02.817] error: *** STEP 60134419.0 ON nid005589 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
    slurm-60134420.out: [2026-10-23T20:38:02.822] error: *** STEP 60134420.0 ON nid005873 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
    slurm-60134421.out: [2026-10-23T20:38:02.821] error: *** STEP 60134421.0 ON nid006242 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***

======================================================================
2026-10-24 06:47 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
Result: finished

Jobs in queue: 5 of limit 100

Folders to submit: 11
  mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
  mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
Submitted job 60205818: mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Submitted job 60205819: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
Submitted job 60205820: mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best
Submitted job 60205821: mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
Submitted job 60205822: mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Submitted job 60205823: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Submitted job 60205825: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best
Submitted job 60205827: mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Submitted job 60205829: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
Submitted job 60205830: mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
Submitted job 60205831: mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best

Submitted: 11

======================================================================
2026-10-24 06:47 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
$ vtriage status /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 16
  pending: 11
  running: 5
  free slots under limit 100: 84

Folders under .: 28
  converged: 2
  crashed: 13
  SCF diverged: 12
  missing inputs: 1

Needs a look:
  mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best [SCF diverged]
  mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-24 06:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
$ vtriage list crashed SCF diverged incomplete
Result: 25 folders

crashed | mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
    slurm-60130645.out: [2026-10-23T15:58:39.122] error: *** STEP 60130645.0 ON nid004215 CANCELLED AT 2026-10-23T15:58:39 DUE TO TIME LIMIT ***
SCF diverged | mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
    slurm-60130647.out: [2026-10-23T15:32:27.646] error: *** STEP 60130647.0 ON nid005089 CANCELLED AT 2026-10-23T15:32:27 DUE TO TASK FAILURE ***
    last SCF energy -2.21e+10 eV, -5.13e+07 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60130650.out: [2026-10-23T16:46:52.594] error: *** STEP 60130650.0 ON nid006020 CANCELLED AT 2026-10-23T16:46:52 DUE TO TIME LIMIT ***
    last SCF energy -3.12e+11 eV, -7.25e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60130652.out: [2026-10-23T17:13:05.931] error: *** STEP 60130652.0 ON nid006359 CANCELLED AT 2026-10-23T17:13:05 DUE TO TIME LIMIT ***
    last SCF energy -2.47e+10 eV, -5.73e+07 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
    slurm-60130655.out: [2026-10-23T16:33:51.024] error: *** STEP 60130655.0 ON nid004234 CANCELLED AT 2026-10-23T16:33:51 DUE TO TASK FAILURE ***
    last SCF energy -5.67e+09 eV, -1.32e+07 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60130661.out: [2026-10-23T17:43:38.162] error: *** STEP 60130661.0 ON nid006061 CANCELLED AT 2026-10-23T17:43:38 DUE TO TIME LIMIT ***
    last SCF energy -5.25e+07 eV, -1.22e+05 eV per atom, check POSCAR and POTCAR
crashed | mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best
    slurm-60130663.out: [2026-10-23T18:04:04.123] error: *** STEP 60130663.0 ON nid004352 CANCELLED AT 2026-10-23T18:04:04 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
    slurm-60130665.out: [2026-10-23T18:04:04.123] error: *** STEP 60130665.0 ON nid004751 CANCELLED AT 2026-10-23T18:04:04 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-27PM/T_0100K/Best_of_Best
    slurm-60130666.out: [2026-10-23T18:30:09.175] error: *** JOB 60130666 ON nid004306 CANCELLED AT 2026-10-23T18:30:09 DUE TO TIME LIMIT ***
SCF diverged | mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
    slurm-60130667.out: [2026-10-23T18:30:09.175] error: *** STEP 60130667.0 ON nid004318 CANCELLED AT 2026-10-23T18:30:09 DUE TO TIME LIMIT ***
    last SCF energy -1.56e+07 eV, -3.64e+04 eV per atom, check POSCAR and POTCAR
crashed | mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60130669.out: [2026-10-23T18:42:09.746] error: *** STEP 60130669.0 ON nid005088 CANCELLED AT 2026-10-23T18:42:09 DUE TO TIME LIMIT ***
SCF diverged | mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
    slurm-60130670.out: [2026-10-23T18:30:45.912] error: *** STEP 60130670.0 ON nid005127 CANCELLED AT 2026-10-23T18:30:45 DUE TO TASK FAILURE ***
    last SCF energy -2.33e+10 eV, -5.42e+07 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
    slurm-60130671.out: [2026-10-23T18:38:10.494] error: *** STEP 60130671.0 ON nid005235 CANCELLED AT 2026-10-23T18:38:10 DUE TO TASK FAILURE ***
    last SCF energy -3.3e+09 eV, -7.68e+06 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
    slurm-60130672.out: [2026-10-23T18:21:50.458] error: *** STEP 60130672.0 ON nid004663 CANCELLED AT 2026-10-23T18:21:50 DUE TO TASK FAILURE ***
    last SCF energy -1.51e+13 eV, -3.51e+10 eV per atom, check POSCAR and POTCAR
crashed | mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
    slurm-60130676.out: [2026-10-23T19:26:04.981] error: *** STEP 60130676.0 ON nid005671 CANCELLED AT 2026-10-23T19:26:04 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
    slurm-60130678.out: [2026-10-23T19:38:47.892] error: *** STEP 60130678.0 ON nid006073 CANCELLED AT 2026-10-23T19:38:47 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
    slurm-60130680.out: [2026-10-23T19:42:35.820] error: *** STEP 60130680.0 ON nid005116 CANCELLED AT 2026-10-23T19:42:35 DUE TO TIME LIMIT ***
SCF diverged | mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
    slurm-60130681.out: [2026-10-23T20:17:10.209] error: *** STEP 60130681.0 ON nid007055 CANCELLED AT 2026-10-23T20:17:10 DUE TO TIME LIMIT ***
    last SCF energy -7.23e+10 eV, -1.69e+08 eV per atom, check POSCAR and POTCAR
crashed | mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
    slurm-60130697.out: [2026-10-23T19:49:44.728] error: *** STEP 60130697.0 ON nid006777 CANCELLED AT 2026-10-23T19:49:44 DUE TO TASK FAILURE ***
SCF diverged | mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
    slurm-60130699.out: [2026-10-23T19:17:16.787] error: *** STEP 60130699.0 ON nid006804 CANCELLED AT 2026-10-23T19:17:16 DUE TO TASK FAILURE ***
    last SCF energy -1.84e+07 eV, -4.31e+04 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
    slurm-60130700.out: [2026-10-23T19:55:01.492] error: *** STEP 60130700.0 ON nid005578 CANCELLED AT 2026-10-23T19:55:01 DUE TO TASK FAILURE ***
    last SCF energy -9.97e+09 eV, -2.33e+07 eV per atom, check POSCAR and POTCAR
crashed | mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
    slurm-60130701.out: [2026-10-23T20:34:12.245] error: *** STEP 60130701.0 ON nid006383 CANCELLED AT 2026-10-23T20:34:12 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
    slurm-60130702.out: [2026-10-23T20:34:14.256] error: *** STEP 60130702.0 ON nid006519 CANCELLED AT 2026-10-23T20:34:14 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
    slurm-60130703.out: [2026-10-23T20:34:14.254] error: *** STEP 60130703.0 ON nid006899 CANCELLED AT 2026-10-23T20:34:14 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-54PM/T_0100K/Best_of_Best
    slurm-60130704.out: [2026-10-23T20:38:02.817] error: *** STEP 60130704.0 ON nid006169 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***

======================================================================
2026-10-24 06:49 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5
Result: finished

Jobs in queue: 16 of limit 100

Folders to submit: 13
  mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-27PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
  mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-54PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
Submitted job 60205880: mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best
Submitted job 60205881: mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
Submitted job 60205882: mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-27PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-27PM/T_0100K/Best_of_Best
Submitted job 60205884: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-27PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Submitted job 60205886: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Submitted job 60205888: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
Submitted job 60205889: mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
Submitted job 60205890: mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
Submitted job 60205891: mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
Submitted job 60205893: mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
Submitted job 60205894: mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
Submitted job 60205895: mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-54PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-54PM/T_0100K/Best_of_Best
Submitted job 60205902: mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-54PM/T_0100K/Best_of_Best

Submitted: 13

======================================================================
2026-10-26 08:08 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 100: 100

Folders under .: 10
  converged: 9
  missing inputs: 1

======================================================================
2026-10-26 08:09 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 100: 100

Folders under .: 10
  converged: 9
  missing inputs: 1

======================================================================
2026-10-26 08:09 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 10 folders

missing inputs | .
    missing: POSCAR, POTCAR
converged | mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best | -5587.76234591 eV
converged | mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best | -5587.76229245 eV
converged | mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best | -5599.57957768 eV
converged | mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best | -5598.90556955 eV
converged | mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best | -5597.89158739 eV
converged | mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best | -5595.37772343 eV
converged | mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best | -5594.42438105 eV
converged | mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best | -5590.47930228 eV
converged | mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best | -5590.28180853 eV

======================================================================
2026-10-26 08:12 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 0 of limit 100

Folders to submit: 1
  mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60309605: mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 08:12 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6/mc_runs
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 1
  pending: 1
  free slots under limit 100: 99

Folders under .: 8
  converged: 7
  SCF diverged: 1

Needs a look:
  2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 08:13 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 9 folders

missing inputs | .
    missing: POSCAR, POTCAR
converged | mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best | -5587.48648865 eV
SCF diverged | mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
    slurm-60204495.out: [2026-10-24T11:59:07.853] error: *** STEP 60204495.0 ON nid005238 CANCELLED AT 2026-10-24T11:59:07 DUE TO TASK FAILURE ***
    last SCF energy -2.84e+10 eV, -6.57e+07 eV per atom, check POSCAR and POTCAR
converged | mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best | -5598.89761407 eV
converged | mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best | -5597.89176512 eV
converged | mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best | -5595.43980543 eV
converged | mc_runs/6-6Y/MC_Run_22Oct2026_12-02PM/T_0100K/Best_of_Best | -5594.21664938 eV
converged | mc_runs/8-8Y/MC_Run_22Oct2026_12-06PM/T_0100K/Best_of_Best | -5590.25872811 eV
converged | mc_runs/9-9Y/MC_Run_22Oct2026_12-07PM/T_0100K/Best_of_Best | -5589.97591028 eV

======================================================================
2026-10-26 08:14 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 1
  pending: 1
  free slots under limit 100: 99

Folders under .: 10
  converged: 7
  SCF diverged: 1
  not submitted: 1
  missing inputs: 1

Needs a look:
  mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 08:15 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage list running or pending not submitted missing inputs
Result: 2 folders

missing inputs | .
    missing: POSCAR, POTCAR
not submitted | mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best

======================================================================
2026-10-26 08:15 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
Result: finished

Jobs in queue: 1 of limit 100

Folders to submit: 1
  mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60309680: mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 08:16 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6 --set ALGO=All
Result: finished


mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 1
Type yes to save each run and apply the changes: Archived as run 1: mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
Changed: mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best

======================================================================
2026-10-26 08:19 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6 --force
Result: finished

Jobs in queue: 2 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best

Folders to submit: 1
  mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60309788: mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 08:33 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 3
  running: 3
  free slots under limit 100: 97

Folders under .: 9
  converged: 4
  crashed: 1
  SCF diverged: 4

Needs a look:
  2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best [SCF diverged]
  4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best [SCF diverged]
  7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 08:35 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac --set ALGO=All
Result: finished


2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 4
Type yes to save each run and apply the changes: Archived as run 1: 2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
Changed: 2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
Archived as run 1: 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Changed: 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Archived as run 1: 5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
Changed: 5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
Archived as run 1: 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Changed: 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best

======================================================================
2026-10-26 08:35 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac
$ vtriage submit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac --force
Result: finished

Jobs in queue: 3 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: 2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best

Folders to submit: 4
  2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
  4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
  5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
  7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60310208: 2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
Submitted job 60310210: 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Submitted job 60310211: 5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
Submitted job 60310212: 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best

Submitted: 4

======================================================================
2026-10-26 08:36 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 9 folders

converged | 10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best | -5573.15836117 eV
running or pending | 2-2Y/MC_Run_22Oct2026_03-30PM/T_0100K/Best_of_Best
crashed | 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60206012.out: [2026-10-24T23:55:42.199] error: *** STEP 60206012.0 ON nid005838 CANCELLED AT 2026-10-24T23:55:42 DUE TO TIME LIMIT ***
running or pending | 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
running or pending | 5-5Y/MC_Run_22Oct2026_03-40PM/T_0100K/Best_of_Best
converged | 6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best | -5579.29685195 eV
running or pending | 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
converged | 8-8Y/MC_Run_22Oct2026_03-50PM/T_0100K/Best_of_Best | -5575.875811 eV
converged | 9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best | -5575.47177757 eV

======================================================================
2026-10-26 08:37 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac
$ vtriage list crashed SCF diverged incomplete
Result: 1 folders

crashed | 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60206012.out: [2026-10-24T23:55:42.199] error: *** STEP 60206012.0 ON nid005838 CANCELLED AT 2026-10-24T23:55:42 DUE TO TIME LIMIT ***

======================================================================
2026-10-26 08:37 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/1-model_trained_on_5x5x5/mc_runs_1vac
Result: finished

Jobs in queue: 7 of limit 100

Folders to submit: 1
  3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 1: 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Submitted job 60310253: 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 08:39 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 8
  pending: 5
  running: 3
  free slots under limit 100: 92

Folders under .: 9
  converged: 4
  crashed: 1
  SCF diverged: 4

Needs a look:
  2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best [SCF diverged]
  4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best [SCF diverged]
  7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 08:40 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 9 folders

converged | 10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best | -5573.15889818 eV
SCF diverged | 2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60134404.out: [2026-10-23T20:38:02.818] error: *** STEP 60134404.0 ON nid004900 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -2.85e+11 eV, -6.6e+08 eV per atom, check POSCAR and POTCAR
crashed | 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60205819.out: [2026-10-24T12:54:16.362] error: *** STEP 60205819.0 ON nid005057 CANCELLED AT 2026-10-24T12:54:16 DUE TO TIME LIMIT ***
SCF diverged | 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60134406.out: [2026-10-23T20:38:02.817] error: *** STEP 60134406.0 ON nid005511 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -3.42e+11 eV, -7.94e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | 5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60134407.out: [2026-10-23T20:38:02.819] error: *** STEP 60134407.0 ON nid005515 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -6.95e+10 eV, -1.61e+08 eV per atom, check POSCAR and POTCAR
converged | 6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best | -5578.38325344 eV
SCF diverged | 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60134409.out: [2026-10-23T20:38:02.817] error: *** STEP 60134409.0 ON nid004529 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -1.04e+07 eV, -2.42e+04 eV per atom, check POSCAR and POTCAR
converged | 8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best | -5575.87601301 eV
converged | 9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best | -5575.4718731 eV

======================================================================
2026-10-26 08:40 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage list converged
Result: 4 folders

converged | 10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best | -5573.15889818 eV
converged | 6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best | -5578.38325344 eV
converged | 8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best | -5575.87601301 eV
converged | 9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best | -5575.4718731 eV

======================================================================
2026-10-26 09:50 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 8 of limit 100
No folders selected.

======================================================================
2026-10-26 09:52 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 8 of limit 100
No folders selected.

======================================================================
2026-10-26 09:56 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 8 of limit 100

Folders to submit: 9
  10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best
  2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
  3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
  4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
  5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
  6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
  7-7Y/MC_Run_26Oct2026_09-23AM/T_0100K/Best_of_Best
  8-8Y/MC_Run_26Oct2026_09-27AM/T_0100K/Best_of_Best
  9-9Y/MC_Run_26Oct2026_09-30AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60312265: 10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best
Submitted job 60312267: 2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
Submitted job 60312269: 3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
Submitted job 60312270: 4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
Submitted job 60312271: 5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
Submitted job 60312272: 6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
Submitted job 60312273: 7-7Y/MC_Run_26Oct2026_09-23AM/T_0100K/Best_of_Best
Submitted job 60312274: 8-8Y/MC_Run_26Oct2026_09-27AM/T_0100K/Best_of_Best
Submitted job 60312275: 9-9Y/MC_Run_26Oct2026_09-30AM/T_0100K/Best_of_Best

Submitted: 9

======================================================================
2026-10-26 11:29 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 10
  running: 10
  free slots under limit 100: 90

Folders under .: 10
  converged: 9
  SCF diverged: 1

Needs a look:
  mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 11:29 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4 --set ALGO=All
Result: finished


mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 1
Type yes to save each run and apply the changes: Archived as run 1: mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
Changed: mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best

======================================================================
2026-10-26 11:30 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage submit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4 --force
Result: finished

Jobs in queue: 10 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best

Folders to submit: 1
  mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60317382: mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 11:30 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 11
  pending: 1
  running: 10
  free slots under limit 100: 89

Folders under .: 10
  converged: 8
  SCF diverged: 1
  missing inputs: 1

Needs a look:
  mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 11:31 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6 --set ALGO=All
Result: finished


mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 1
Type yes to save each run and apply the changes: Archived as run 1: mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
Changed: mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best

======================================================================
2026-10-26 11:32 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6 --force
Result: finished

Jobs in queue: 11 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best

Folders to submit: 1
  mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60317471: mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 11:39 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 11
  pending: 2
  running: 9
  free slots under limit 100: 89

Folders under .: 9
  converged: 4
  crashed: 1
  SCF diverged: 4

Needs a look:
  2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best [SCF diverged]
  4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best [SCF diverged]
  7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 11:39 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 9 folders

converged | 10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best | -5573.15889818 eV
SCF diverged | 2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60134404.out: [2026-10-23T20:38:02.818] error: *** STEP 60134404.0 ON nid004900 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -2.85e+11 eV, -6.6e+08 eV per atom, check POSCAR and POTCAR
crashed | 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60205819.out: [2026-10-24T12:54:16.362] error: *** STEP 60205819.0 ON nid005057 CANCELLED AT 2026-10-24T12:54:16 DUE TO TIME LIMIT ***
SCF diverged | 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60134406.out: [2026-10-23T20:38:02.817] error: *** STEP 60134406.0 ON nid005511 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -3.42e+11 eV, -7.94e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | 5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60134407.out: [2026-10-23T20:38:02.819] error: *** STEP 60134407.0 ON nid005515 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -6.95e+10 eV, -1.61e+08 eV per atom, check POSCAR and POTCAR
converged | 6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best | -5578.38325344 eV
SCF diverged | 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60134409.out: [2026-10-23T20:38:02.817] error: *** STEP 60134409.0 ON nid004529 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -1.04e+07 eV, -2.42e+04 eV per atom, check POSCAR and POTCAR
converged | 8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best | -5575.87601301 eV
converged | 9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best | -5575.4718731 eV

======================================================================
2026-10-26 11:40 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage list converged
Result: 4 folders

converged | 10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best | -5573.15889818 eV
converged | 6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best | -5578.38325344 eV
converged | 8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best | -5575.87601301 eV
converged | 9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best | -5575.4718731 eV

======================================================================
2026-10-26 11:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage status
Result: checked

Jobs from this folder: 9
  running: 9

All my jobs in the queue: 11
  pending: 2
  running: 9
  free slots under limit 100: 89

Folders under .: 9
  running or pending: 9

======================================================================
2026-10-26 11:43 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 11
  pending: 1
  running: 10
  free slots under limit 100: 89

Folders under .: 9
  not submitted: 9

======================================================================
2026-10-26 11:43 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 11 of limit 100

Folders to submit: 9
  10-10Y/MC_Run_26Oct2026_10-29AM/T_0100K/Best_of_Best
  2-2Y/MC_Run_26Oct2026_10-02AM/T_0100K/Best_of_Best
  3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
  4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
  5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
  6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
  7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
  8-8Y/MC_Run_26Oct2026_10-22AM/T_0100K/Best_of_Best
  9-9Y/MC_Run_26Oct2026_10-26AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60317841: 10-10Y/MC_Run_26Oct2026_10-29AM/T_0100K/Best_of_Best
Submitted job 60317842: 2-2Y/MC_Run_26Oct2026_10-02AM/T_0100K/Best_of_Best
Submitted job 60317843: 3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
Submitted job 60317844: 4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
Submitted job 60317845: 5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
Submitted job 60317848: 6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
Submitted job 60317849: 7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
Submitted job 60317850: 8-8Y/MC_Run_26Oct2026_10-22AM/T_0100K/Best_of_Best
Submitted job 60317851: 9-9Y/MC_Run_26Oct2026_10-26AM/T_0100K/Best_of_Best

Submitted: 9

======================================================================
2026-10-26 11:44 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac
$ vtriage submit --status not submitted
Result: finished

Jobs in queue: 20 of limit 100

Folders to submit: 9
  10-10Y/MC_Run_26Oct2026_11-15AM/T_0100K/Best_of_Best
  2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
  3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
  4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
  5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best
  6-6Y/MC_Run_26Oct2026_11-01AM/T_0100K/Best_of_Best
  7-7Y/MC_Run_26Oct2026_11-05AM/T_0100K/Best_of_Best
  8-8Y/MC_Run_26Oct2026_11-08AM/T_0100K/Best_of_Best
  9-9Y/MC_Run_26Oct2026_11-12AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60317913: 10-10Y/MC_Run_26Oct2026_11-15AM/T_0100K/Best_of_Best
Submitted job 60317914: 2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
Submitted job 60317915: 3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
Submitted job 60317917: 4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
Submitted job 60317918: 5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best
Submitted job 60317919: 6-6Y/MC_Run_26Oct2026_11-01AM/T_0100K/Best_of_Best
Submitted job 60317920: 7-7Y/MC_Run_26Oct2026_11-05AM/T_0100K/Best_of_Best
Submitted job 60317922: 8-8Y/MC_Run_26Oct2026_11-08AM/T_0100K/Best_of_Best
Submitted job 60317923: 9-9Y/MC_Run_26Oct2026_11-12AM/T_0100K/Best_of_Best

Submitted: 9

======================================================================
2026-10-26 13:33 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 21
  pending: 10
  running: 11
  free slots under limit 100: 79

Folders under .: 9
  converged: 4
  crashed: 1
  SCF diverged: 4

Needs a look:
  2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best [SCF diverged]
  4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best [SCF diverged]
  7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 13:33 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage list converged
Result: 4 folders

converged | 10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best | -5573.15889818 eV
converged | 6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best | -5578.38325344 eV
converged | 8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best | -5575.87601301 eV
converged | 9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best | -5575.4718731 eV

======================================================================
2026-10-26 13:43 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage list crashed SCF diverged incomplete
Result: 5 folders

SCF diverged | 2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60134404.out: [2026-10-23T20:38:02.818] error: *** STEP 60134404.0 ON nid004900 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -2.85e+11 eV, -6.6e+08 eV per atom, check POSCAR and POTCAR
crashed | 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60205819.out: [2026-10-24T12:54:16.362] error: *** STEP 60205819.0 ON nid005057 CANCELLED AT 2026-10-24T12:54:16 DUE TO TIME LIMIT ***
SCF diverged | 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60134406.out: [2026-10-23T20:38:02.817] error: *** STEP 60134406.0 ON nid005511 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -3.42e+11 eV, -7.94e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | 5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60134407.out: [2026-10-23T20:38:02.819] error: *** STEP 60134407.0 ON nid005515 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -6.95e+10 eV, -1.61e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60134409.out: [2026-10-23T20:38:02.817] error: *** STEP 60134409.0 ON nid004529 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -1.04e+07 eV, -2.42e+04 eV per atom, check POSCAR and POTCAR

======================================================================
2026-10-26 13:44 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac --set ALGO=All
Result: finished


2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 4
Type yes to save each run and apply the changes: Archived as run 1: 2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Changed: 2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Archived as run 1: 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Changed: 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Archived as run 1: 5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Changed: 5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Archived as run 1: 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Changed: 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best

======================================================================
2026-10-26 13:44 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage submit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac --force
Result: finished

Jobs in queue: 19 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: 2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best

Folders to submit: 4
  2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
  4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
  5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
  7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60321242: 2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Submitted job 60321245: 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Submitted job 60321246: 5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Submitted job 60321247: 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best

Submitted: 4

======================================================================
2026-10-26 13:44 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage list crashed SCF diverged incomplete
Result: 1 folders

crashed | 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60205819.out: [2026-10-24T12:54:16.362] error: *** STEP 60205819.0 ON nid005057 CANCELLED AT 2026-10-24T12:54:16 DUE TO TIME LIMIT ***

======================================================================
2026-10-26 13:47 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 23
  pending: 13
  running: 10
  free slots under limit 100: 77

Folders under .: 9
  converged: 2
  crashed: 3
  SCF diverged: 4

Needs a look:
  2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best [SCF diverged]
  4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best [SCF diverged]
  6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 13:47 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 9 folders

crashed | 10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60205823.out: [2026-10-24T13:19:34.104] error: *** STEP 60205823.0 ON nid004156 CANCELLED AT 2026-10-24T13:19:34 DUE TO TIME LIMIT ***
SCF diverged | 2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
    slurm-60134413.out: [2026-10-23T20:38:02.819] error: *** STEP 60134413.0 ON nid006354 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -1.87e+10 eV, -4.35e+07 eV per atom, check POSCAR and POTCAR
crashed | 3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60205825.out: [2026-10-24T13:19:34.112] error: *** STEP 60205825.0 ON nid005254 CANCELLED AT 2026-10-24T13:19:34 DUE TO TIME LIMIT ***
SCF diverged | 4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
    slurm-60134415.out: [2026-10-23T19:43:27.323] error: *** STEP 60134415.0 ON nid006698 CANCELLED AT 2026-10-23T19:43:27 DUE TO TASK FAILURE ***
    last SCF energy -1.84e+07 eV, -4.28e+04 eV per atom, check POSCAR and POTCAR
SCF diverged | 5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
    slurm-60134416.out: [2026-10-23T20:34:41.881] error: *** STEP 60134416.0 ON nid004675 CANCELLED AT 2026-10-23T20:34:41 DUE TO TASK FAILURE ***
    last SCF energy -7.74e+10 eV, -1.8e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | 6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
    slurm-60134417.out: [2026-10-23T20:38:02.819] error: *** STEP 60134417.0 ON nid005057 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -5.59e+08 eV, -1.3e+06 eV per atom, check POSCAR and POTCAR
converged | 7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best | -5562.6760141 eV
crashed | 8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
    slurm-60205829.out: [2026-10-24T13:29:18.051] error: *** STEP 60205829.0 ON nid005839 CANCELLED AT 2026-10-24T13:29:18 DUE TO TIME LIMIT ***
converged | 9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best | -5559.91199936 eV

======================================================================
2026-10-26 13:47 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage list converged
Result: 2 folders

converged | 7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best | -5562.6760141 eV
converged | 9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best | -5559.91199936 eV

======================================================================
2026-10-26 13:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage list crashed SCF diverged incomplete
Result: 7 folders

crashed | 10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60205823.out: [2026-10-24T13:19:34.104] error: *** STEP 60205823.0 ON nid004156 CANCELLED AT 2026-10-24T13:19:34 DUE TO TIME LIMIT ***
SCF diverged | 2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
    slurm-60134413.out: [2026-10-23T20:38:02.819] error: *** STEP 60134413.0 ON nid006354 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -1.87e+10 eV, -4.35e+07 eV per atom, check POSCAR and POTCAR
crashed | 3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60205825.out: [2026-10-24T13:19:34.112] error: *** STEP 60205825.0 ON nid005254 CANCELLED AT 2026-10-24T13:19:34 DUE TO TIME LIMIT ***
SCF diverged | 4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
    slurm-60134415.out: [2026-10-23T19:43:27.323] error: *** STEP 60134415.0 ON nid006698 CANCELLED AT 2026-10-23T19:43:27 DUE TO TASK FAILURE ***
    last SCF energy -1.84e+07 eV, -4.28e+04 eV per atom, check POSCAR and POTCAR
SCF diverged | 5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
    slurm-60134416.out: [2026-10-23T20:34:41.881] error: *** STEP 60134416.0 ON nid004675 CANCELLED AT 2026-10-23T20:34:41 DUE TO TASK FAILURE ***
    last SCF energy -7.74e+10 eV, -1.8e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | 6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
    slurm-60134417.out: [2026-10-23T20:38:02.819] error: *** STEP 60134417.0 ON nid005057 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -5.59e+08 eV, -1.3e+06 eV per atom, check POSCAR and POTCAR
crashed | 8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
    slurm-60205829.out: [2026-10-24T13:29:18.051] error: *** STEP 60205829.0 ON nid005839 CANCELLED AT 2026-10-24T13:29:18 DUE TO TIME LIMIT ***

======================================================================
2026-10-26 14:49 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac --set ALGO=All
Result: finished


2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 4
Type yes to save each run and apply the changes: Archived as run 1: 2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Changed: 2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Archived as run 1: 4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Changed: 4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Archived as run 1: 5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Changed: 5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Archived as run 1: 6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
Changed: 6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best

======================================================================
2026-10-26 14:50 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage submit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac --force
Result: finished

Jobs in queue: 20 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: 2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best

Folders to submit: 4
  2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
  4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
  5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
  6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60326402: 2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Submitted job 60326403: 4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Submitted job 60326405: 5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Submitted job 60326406: 6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best

Submitted: 4

======================================================================
2026-10-26 14:50 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage status /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
Result: checked

Jobs from this folder: 4
  pending: 4

All my jobs in the queue: 24
  pending: 13
  running: 11
  free slots under limit 100: 76

Folders under .: 9
  converged: 2
  crashed: 3
  running or pending: 4

======================================================================
2026-10-26 14:50 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 9 folders

crashed | 10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60205823.out: [2026-10-24T13:19:34.104] error: *** STEP 60205823.0 ON nid004156 CANCELLED AT 2026-10-24T13:19:34 DUE TO TIME LIMIT ***
running or pending | 2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
crashed | 3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60205825.out: [2026-10-24T13:19:34.112] error: *** STEP 60205825.0 ON nid005254 CANCELLED AT 2026-10-24T13:19:34 DUE TO TIME LIMIT ***
running or pending | 4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
running or pending | 5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
running or pending | 6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
converged | 7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best | -5562.6760141 eV
crashed | 8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
    slurm-60205829.out: [2026-10-24T13:29:18.051] error: *** STEP 60205829.0 ON nid005839 CANCELLED AT 2026-10-24T13:29:18 DUE TO TIME LIMIT ***
converged | 9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best | -5559.91199936 eV

======================================================================
2026-10-26 14:52 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 24
  pending: 13
  running: 11
  free slots under limit 100: 76

Folders under .: 9
  converged: 1
  SCF diverged: 1
  not submitted: 7

Needs a look:
  2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 14:52 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 9 folders

converged | 10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best | -5528.01851002 eV
SCF diverged | 2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
    slurm-60134423.out: [2026-10-23T20:38:02.826] error: *** STEP 60134423.0 ON nid006474 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -4.97e+10 eV, -1.16e+08 eV per atom, check POSCAR and POTCAR
not submitted | 3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
not submitted | 4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
not submitted | 5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
not submitted | 6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
not submitted | 7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
not submitted | 8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
not submitted | 9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best

======================================================================
2026-10-26 14:53 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac
$ vtriage submit --status not submitted --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac
Result: finished

Jobs in queue: 24 of limit 100

Folders to submit: 7
  3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
  4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
  5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
  6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
  7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
  8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
  9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60326722: 3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
Submitted job 60326723: 4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
Submitted job 60326724: 5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
Submitted job 60326725: 6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
Submitted job 60326726: 7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
Submitted job 60326727: 8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
Submitted job 60326728: 9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best

Submitted: 7

======================================================================
2026-10-26 14:53 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 9 folders

converged | 10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best | -5528.01851002 eV
SCF diverged | 2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
    slurm-60134423.out: [2026-10-23T20:38:02.826] error: *** STEP 60134423.0 ON nid006474 CANCELLED AT 2026-10-23T20:38:02 DUE TO TIME LIMIT ***
    last SCF energy -4.97e+10 eV, -1.16e+08 eV per atom, check POSCAR and POTCAR
running or pending | 3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
running or pending | 4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
running or pending | 5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
running or pending | 6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
running or pending | 7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
running or pending | 8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
running or pending | 9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best

======================================================================
2026-10-26 14:53 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac --set ALGO=All
Result: finished


2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 1
Type yes to save each run and apply the changes: Archived as run 1: 2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
Changed: 2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best

======================================================================
2026-10-26 14:54 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac --force
Result: finished

Jobs in queue: 31 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: 2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best

Folders to submit: 1
  2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60326783: 2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 15:47 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 30
  pending: 17
  running: 13
  free slots under limit 100: 70

Folders under .: 10
  converged: 9
  crashed: 1

======================================================================
2026-10-26 15:47 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 30
  pending: 17
  running: 13
  free slots under limit 100: 70

Folders under .: 10
  converged: 9
  crashed: 1

======================================================================
2026-10-26 15:47 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 10 folders

converged | mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best | -5587.76234591 eV
converged | mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best | -5587.76229245 eV
converged | mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best | -5599.57957768 eV
converged | mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best | -5598.90556955 eV
converged | mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best | -5597.89158739 eV
converged | mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best | -5595.37772343 eV
converged | mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best | -5594.42438105 eV
crashed | mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
    slurm-60317382.out: [2026-10-26T17:41:55.592] error: *** STEP 60317382.0 ON nid004781 CANCELLED AT 2026-10-26T17:41:55 DUE TO TIME LIMIT ***
converged | mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best | -5590.47930228 eV
converged | mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best | -5590.28180853 eV

======================================================================
2026-10-26 15:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list crashed SCF diverged incomplete
Result: 1 folders

crashed | mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
    slurm-60317382.out: [2026-10-26T17:41:55.592] error: *** STEP 60317382.0 ON nid004781 CANCELLED AT 2026-10-26T17:41:55 DUE TO TIME LIMIT ***

======================================================================
2026-10-26 15:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
Result: finished

Jobs in queue: 30 of limit 100

Folders to submit: 1
  mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 2: mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
Submitted job 60330578: mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 15:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 31
  pending: 18
  running: 13
  free slots under limit 100: 69

Folders under .: 10
  converged: 8
  crashed: 1
  missing inputs: 1

======================================================================
2026-10-26 15:49 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 10 folders

missing inputs | .
    missing: POSCAR, POTCAR
converged | mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best | -5587.48648865 eV
converged | mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best | -5599.64431065 eV
converged | mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best | -5598.89761407 eV
converged | mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best | -5597.89176512 eV
converged | mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best | -5595.43980543 eV
converged | mc_runs/6-6Y/MC_Run_22Oct2026_12-02PM/T_0100K/Best_of_Best | -5594.21664938 eV
crashed | mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
    slurm-60317471.out: [2026-10-26T17:45:02.450] error: *** STEP 60317471.0 ON nid004941 CANCELLED AT 2026-10-26T17:45:02 DUE TO TIME LIMIT ***
converged | mc_runs/8-8Y/MC_Run_22Oct2026_12-06PM/T_0100K/Best_of_Best | -5590.25872811 eV
converged | mc_runs/9-9Y/MC_Run_22Oct2026_12-07PM/T_0100K/Best_of_Best | -5589.97591028 eV

======================================================================
2026-10-26 15:50 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
Result: finished

Jobs in queue: 31 of limit 100

Folders to submit: 1
  mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 2: mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
Submitted job 60330642: mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-26 19:35 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac
$ vtriage status
Result: checked

Jobs from this folder: 2
  pending: 2

All my jobs in the queue: 12
  pending: 9
  running: 3
  free slots under limit 100: 88

Folders under .: 20
  converged: 17
  running or pending: 2
  missing inputs: 1

======================================================================
2026-10-26 19:36 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 12
  pending: 9
  running: 3
  free slots under limit 100: 88

Folders under .: 9
  converged: 3
  crashed: 1
  SCF diverged: 5

Needs a look:
  2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best [SCF diverged]
  3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best [SCF diverged]
  4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best [SCF diverged]
  6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 19:36 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage list converged
Result: 3 folders

converged | 7-7Y/MC_Run_26Oct2026_09-23AM/T_0100K/Best_of_Best | -5579.50809197 eV
converged | 8-8Y/MC_Run_26Oct2026_09-27AM/T_0100K/Best_of_Best | -5576.95625713 eV
    slurm-60312274.out: DAV:  41    -0.575024350225E+04   -0.17380E+03   -0.46801E-03  9504   0.492E-02BRMIX: very serious problems
converged | 9-9Y/MC_Run_26Oct2026_09-30AM/T_0100K/Best_of_Best | -5576.21012861 eV
    slurm-60312275.out: DAV:  43    -0.661933486952E+04   -0.10437E+04   -0.49014E-05  6272   0.872E-03BRMIX: very serious problems

======================================================================
2026-10-26 19:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage list crashed SCF diverged incomplete
Result: 6 folders

crashed | 10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best
    slurm-60312265.out: [2026-10-26T18:11:31.700] error: *** STEP 60312265.0 ON nid004489 CANCELLED AT 2026-10-26T18:11:31 DUE TO TASK FAILURE ***
SCF diverged | 2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
    slurm-60312267.out: [2026-10-26T16:34:35.270] error: *** STEP 60312267.0 ON nid005454 CANCELLED AT 2026-10-26T16:34:35 DUE TO TASK FAILURE ***
    last SCF energy -1.3e+11 eV, -3.02e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | 3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
    slurm-60312269.out: [2026-10-26T20:15:11.085] error: *** STEP 60312269.0 ON nid006003 CANCELLED AT 2026-10-26T20:15:11 DUE TO TIME LIMIT ***
    last SCF energy -2.23e+07 eV, -5.18e+04 eV per atom, check POSCAR and POTCAR
SCF diverged | 4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
    slurm-60312270.out: [2026-10-26T16:48:40.246] error: *** STEP 60312270.0 ON nid006185 CANCELLED AT 2026-10-26T16:48:40 DUE TO TASK FAILURE ***
    last SCF energy -8.9e+10 eV, -2.07e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | 5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
    slurm-60312271.out: [2026-10-26T16:49:43.794] error: *** STEP 60312271.0 ON nid005060 CANCELLED AT 2026-10-26T16:49:43 DUE TO TASK FAILURE ***
    last SCF energy -1.56e+10 eV, -3.62e+07 eV per atom, check POSCAR and POTCAR
SCF diverged | 6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
    slurm-60312272.out: [2026-10-26T15:53:22.286] error: *** STEP 60312272.0 ON nid005284 CANCELLED AT 2026-10-26T15:53:22 DUE TO TASK FAILURE ***
    last SCF energy -1.86e+07 eV, -4.32e+04 eV per atom, check POSCAR and POTCAR

======================================================================
2026-10-26 19:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac --set ALGO=All
Result: finished


2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 5
Type yes to save each run and apply the changes: Archived as run 1: 2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
Changed: 2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
Archived as run 1: 3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
Changed: 3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
Archived as run 1: 4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
Changed: 4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
Archived as run 1: 5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
Changed: 5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
Archived as run 1: 6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
Changed: 6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best

======================================================================
2026-10-26 19:48 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage submit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac --force
Result: finished

Jobs in queue: 11 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: 2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best

Folders to submit: 5
  2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
  3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
  4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
  5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
  6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60341693: 2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
Submitted job 60341695: 3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
Submitted job 60341701: 4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
Submitted job 60341704: 5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
Submitted job 60341706: 6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best

Submitted: 5

======================================================================
2026-10-26 19:49 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 16
  pending: 14
  running: 2
  free slots under limit 100: 84

Folders under .: 9
  converged: 3
  crashed: 1
  SCF diverged: 5

Needs a look:
  3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best [SCF diverged]
  4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best [SCF diverged]
  6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best [SCF diverged]
  7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 19:49 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac
$ vtriage edit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac --set ALGO=All
Result: finished


3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 5
Type yes to save each run and apply the changes: Archived as run 1: 3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
Changed: 3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
Archived as run 1: 4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
Changed: 4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
Archived as run 1: 5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
Changed: 5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
Archived as run 1: 6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
Changed: 6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
Archived as run 1: 7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
Changed: 7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best

======================================================================
2026-10-26 19:50 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac
$ vtriage submit --status SCF diverged --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac --force
Result: finished

Jobs in queue: 16 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: 3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best

Folders to submit: 5
  3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
  4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
  5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
  6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
  7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60341747: 3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
Submitted job 60341748: 4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
Submitted job 60341749: 5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
Submitted job 60341750: 6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
Submitted job 60341751: 7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best

Submitted: 5

======================================================================
2026-10-26 19:50 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 21
  pending: 19
  running: 2
  free slots under limit 100: 79

Folders under .: 9
  converged: 5
  SCF diverged: 4

Needs a look:
  2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best [SCF diverged]
  3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best [SCF diverged]
  4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-26 19:50 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac
$ vtriage list crashed SCF diverged incomplete
Result: 4 folders

SCF diverged | 2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
    slurm-60317914.out: [2026-10-26T18:47:14.270] error: *** STEP 60317914.0 ON nid004224 CANCELLED AT 2026-10-26T18:47:14 DUE TO TASK FAILURE ***
    last SCF energy -1.12e+08 eV, -2.61e+05 eV per atom, check POSCAR and POTCAR
SCF diverged | 3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
    slurm-60317915.out: [2026-10-26T21:45:33.737] error: *** STEP 60317915.0 ON nid004483 CANCELLED AT 2026-10-26T21:45:33 DUE TO TASK FAILURE ***
    last SCF energy -1.04e+10 eV, -2.44e+07 eV per atom, check POSCAR and POTCAR
SCF diverged | 4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
    slurm-60317917.out: [2026-10-26T19:37:48.880] error: *** STEP 60317917.0 ON nid004152 CANCELLED AT 2026-10-26T19:37:48 DUE TO TASK FAILURE ***
    last SCF energy -4.98e+08 eV, -1.16e+06 eV per atom, check POSCAR and POTCAR
SCF diverged | 5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best
    slurm-60317918.out: [2026-10-26T20:32:27.578] error: *** STEP 60317918.0 ON nid006561 CANCELLED AT 2026-10-26T20:32:27 DUE TO TASK FAILURE ***
    last SCF energy -3.82e+07 eV, -8.92e+04 eV per atom, check POSCAR and POTCAR

======================================================================
2026-10-26 19:51 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac
$ vtriage edit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac --set ALGO=All
Result: finished


2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 4
Type yes to save each run and apply the changes: Archived as run 1: 2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
Changed: 2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
Archived as run 1: 3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
Changed: 3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
Archived as run 1: 4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
Changed: 4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
Archived as run 1: 5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best
Changed: 5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best

======================================================================
2026-10-26 19:51 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac --force
Result: finished

Jobs in queue: 21 of limit 100
Warning: SCF diverged, submitted from POSCAR as it is now: 2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
Warning: SCF diverged, submitted from POSCAR as it is now: 5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best

Folders to submit: 4
  2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
  3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
  4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
  5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60341875: 2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
Submitted job 60341876: 3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
Submitted job 60341878: 4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
Submitted job 60341879: 5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best

Submitted: 4

======================================================================
2026-10-26 19:52 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage status
Result: checked

Jobs from this folder: 9
  pending: 7
  running: 2

All my jobs in the queue: 25
  pending: 23
  running: 2
  free slots under limit 100: 75

Folders under .: 28
  converged: 7
  crashed: 11
  running or pending: 9
  missing inputs: 1

======================================================================
2026-10-26 19:52 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage list crashed SCF diverged incomplete
Result: 11 folders

crashed | mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60321242.out: [2026-10-26T21:59:49.116] error: *** STEP 60321242.0 ON nid006494 CANCELLED AT 2026-10-26T21:59:49 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60321312.out: [2026-10-26T22:57:02.395] error: *** STEP 60321312.0 ON nid005649 CANCELLED AT 2026-10-26T22:57:02 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60321245.out: [2026-10-26T22:01:22.817] error: *** STEP 60321245.0 ON nid006407 CANCELLED AT 2026-10-26T22:01:22 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60321246.out: [2026-10-26T22:28:10.071] error: *** JOB 60321246 ON nid004303 CANCELLED AT 2026-10-26T22:28:10 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60321247.out: [2026-10-26T22:34:17.566] error: *** STEP 60321247.0 ON nid006913 CANCELLED AT 2026-10-26T22:34:17 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60205823.out: [2026-10-24T13:19:34.104] error: *** STEP 60205823.0 ON nid004156 CANCELLED AT 2026-10-24T13:19:34 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
    slurm-60326402.out: [2026-10-26T23:04:13.460] error: *** STEP 60326402.0 ON nid005026 CANCELLED AT 2026-10-26T23:04:13 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60205825.out: [2026-10-24T13:19:34.112] error: *** STEP 60205825.0 ON nid005254 CANCELLED AT 2026-10-24T13:19:34 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
    slurm-60326403.out: [2026-10-26T23:32:44.069] error: *** STEP 60326403.0 ON nid005768 CANCELLED AT 2026-10-26T23:32:44 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
    slurm-60326405.out: [2026-10-26T23:44:44.130] error: *** STEP 60326405.0 ON nid005761 CANCELLED AT 2026-10-26T23:44:44 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
    slurm-60205829.out: [2026-10-24T13:29:18.051] error: *** STEP 60205829.0 ON nid005839 CANCELLED AT 2026-10-24T13:29:18 DUE TO TIME LIMIT ***

======================================================================
2026-10-26 19:52 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage edit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6 --set ALGO=All
Result: finished

No change needed: mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
No change needed: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
No change needed: mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
No change needed: mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
No change needed: mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best

mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
  ALGO: Normal -> All
No change needed: mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best

mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
  ALGO: Normal -> All
No change needed: mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
No change needed: mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best

mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 3
Type yes to save each run and apply the changes: Archived as run 2: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Changed: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Changed: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Changed: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best

======================================================================
2026-10-26 19:53 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6 --force
Result: finished

Jobs in queue: 25 of limit 100
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best

Folders to submit: 11
  mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 2: mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Submitted job 60341922: mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Submitted job 60341923: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Submitted job 60341927: mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Submitted job 60341930: mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Submitted job 60341931: mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Submitted job 60341932: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Submitted job 60341933: mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Submitted job 60341934: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Submitted job 60341937: mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Submitted job 60341940: mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Submitted job 60341941: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best

Submitted: 11

======================================================================
2026-10-27 07:33 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 1
  running: 1

All my jobs in the queue: 27
  pending: 19
  running: 8
  free slots under limit 100: 73

Folders under .: 10
  converged: 9
  running or pending: 1

======================================================================
2026-10-27 07:33 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage status
Result: checked

Jobs from this folder: 1
  running: 1

All my jobs in the queue: 27
  pending: 19
  running: 8
  free slots under limit 100: 73

Folders under .: 10
  converged: 8
  running or pending: 1
  missing inputs: 1

======================================================================
2026-10-27 07:35 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage status
Result: checked

Jobs from this folder: 5
  running: 5

All my jobs in the queue: 27
  pending: 19
  running: 8
  free slots under limit 100: 73

Folders under .: 9
  converged: 3
  crashed: 1
  running or pending: 5

======================================================================
2026-10-27 07:35 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage list running or pending not submitted missing inputs
Result: 5 folders

running or pending | 2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
running or pending | 3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
running or pending | 4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
running or pending | 5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
running or pending | 6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best

======================================================================
2026-10-27 07:35 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage list crashed SCF diverged incomplete
Result: 1 folders

crashed | 10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best
    slurm-60312265.out: [2026-10-26T18:11:31.700] error: *** STEP 60312265.0 ON nid004489 CANCELLED AT 2026-10-26T18:11:31 DUE TO TASK FAILURE ***

======================================================================
2026-10-27 07:36 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage status
Result: checked

Jobs from this folder: 5
  running: 5

All my jobs in the queue: 27
  pending: 19
  running: 8
  free slots under limit 100: 73

Folders under .: 9
  converged: 3
  crashed: 1
  running or pending: 5

======================================================================
2026-10-27 07:36 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage edit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac --set ALGO=All
Result: finished


10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best
  ALGO: Normal -> All

Folders to change: 1
Type yes to save each run and apply the changes: Archived as run 1: 10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best
Changed: 10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best

======================================================================
2026-10-27 07:37 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
$ vtriage submit --status crashed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_1vac
Result: finished

Jobs in queue: 27 of limit 100

Folders to submit: 1
  10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best
Type yes to save each run and submit: Submitted job 60365755: 10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best

Submitted: 1

======================================================================
2026-10-27 07:37 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac
$ vtriage status
Result: checked

Jobs from this folder: 5
  pending: 4
  running: 1

All my jobs in the queue: 28
  pending: 20
  running: 8
  free slots under limit 100: 72

Folders under .: 9
  converged: 3
  crashed: 1
  running or pending: 5

======================================================================
2026-10-27 07:37 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac
$ vtriage list converged
Result: 3 folders

converged | 10-10Y/MC_Run_26Oct2026_10-29AM/T_0100K/Best_of_Best | -5559.30776934 eV
    slurm-60317841.out: DAV:  43    -0.571688560228E+04   -0.15870E+03   -0.10808E-03 10368   0.550E-02BRMIX: very serious problems
converged | 8-8Y/MC_Run_26Oct2026_10-22AM/T_0100K/Best_of_Best | -5561.60420866 eV
converged | 9-9Y/MC_Run_26Oct2026_10-26AM/T_0100K/Best_of_Best | -5561.18688908 eV
    slurm-60317851.out: DAV:  47    -0.594340753890E+04   -0.38295E+03   -0.26808E-03 10464   0.975E-02BRMIX: very serious problems

======================================================================
2026-10-27 07:38 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_2vac
$ vtriage list running or pending not submitted missing inputs
Result: 5 folders

running or pending | 3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
running or pending | 4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
running or pending | 5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
running or pending | 6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
running or pending | 7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best

======================================================================
2026-10-27 07:38 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac
$ vtriage status
Result: checked

Jobs from this folder: 4
  pending: 4

All my jobs in the queue: 28
  pending: 20
  running: 8
  free slots under limit 100: 72

Folders under .: 9
  converged: 5
  running or pending: 4

======================================================================
2026-10-27 07:38 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again/mc_run_4vac
$ vtriage list converged
Result: 5 folders

converged | 10-10Y/MC_Run_26Oct2026_11-15AM/T_0100K/Best_of_Best | -5528.44732129 eV
    slurm-60317913.out: DAV:  40    -0.605986543225E+04   -0.53300E+03   -0.91475E-06  5280   0.896E-03BRMIX: very serious problems
converged | 6-6Y/MC_Run_26Oct2026_11-01AM/T_0100K/Best_of_Best | -5533.10472457 eV
converged | 7-7Y/MC_Run_26Oct2026_11-05AM/T_0100K/Best_of_Best | -5533.03185095 eV
converged | 8-8Y/MC_Run_26Oct2026_11-08AM/T_0100K/Best_of_Best | -5530.93814997 eV
    slurm-60317922.out: DAV:  36    -0.563679185928E+04   -0.10741E+03   -0.39908E-04  8640   0.253E-02BRMIX: very serious problems
converged | 9-9Y/MC_Run_26Oct2026_11-12AM/T_0100K/Best_of_Best | -5530.21215086 eV

======================================================================
2026-10-27 07:40 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/4-model_trained_on_6x6x6_again/mc_runs_1vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 28
  pending: 20
  running: 8
  free slots under limit 100: 72

Folders under .: 0

======================================================================
2026-10-27 07:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage status
Result: checked

Jobs from this folder: 5
  pending: 5

All my jobs in the queue: 28
  pending: 20
  running: 8
  free slots under limit 100: 72

Folders under .: 9
  converged: 4
  running or pending: 5

======================================================================
2026-10-27 07:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_2vac
$ vtriage status
Result: checked

Jobs from this folder: 6
  pending: 6

All my jobs in the queue: 28
  pending: 20
  running: 8
  free slots under limit 100: 72

Folders under .: 9
  converged: 2
  crashed: 1
  running or pending: 6

======================================================================
2026-10-27 07:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_4vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 28
  pending: 20
  running: 8
  free slots under limit 100: 72

Folders under .: 9
  converged: 1
  crashed: 4
  SCF diverged: 4

Needs a look:
  3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best [SCF diverged]
  5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best [SCF diverged]
  6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best [SCF diverged]
  9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best [SCF diverged]

======================================================================
2026-10-27 16:18 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 3
  running: 3
  free slots under limit 100: 97

Folders under .: 10
  converged: 9
  crashed: 1

======================================================================
2026-10-27 16:18 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list crashed SCF diverged incomplete
Result: 1 folders

crashed | mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
    slurm-60330578.out: [2026-10-27T11:47:11.182] error: *** STEP 60330578.0 ON nid005367 CANCELLED AT 2026-10-27T11:47:11 DUE TO TIME LIMIT ***

======================================================================
2026-10-27 16:18 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac
$ vtriage list crashed SCF diverged incomplete
Result: 2 folders

crashed | 1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
    slurm-60330578.out: [2026-10-27T11:47:11.182] error: *** STEP 60330578.0 ON nid005367 CANCELLED AT 2026-10-27T11:47:11 DUE TO TIME LIMIT ***
crashed | 2-model_trained_from_6x6x6/mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
    slurm-60330642.out: [2026-10-27T11:47:11.182] error: *** STEP 60330642.0 ON nid005539 CANCELLED AT 2026-10-27T11:47:11 DUE TO TIME LIMIT ***

======================================================================
2026-10-27 16:19 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac
Result: finished

Jobs in queue: 3 of limit 100
Warning: same error as previous run (walltime). Change settings first: 1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: 2-model_trained_from_6x6x6/mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best

Folders to submit: 2
  1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  2-model_trained_from_6x6x6/mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 3: 1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: 1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
Submitted job 60400043: 1-model_trained_from_4x4x4/mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best
Archived as run 3: 2-model_trained_from_6x6x6/mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: 2-model_trained_from_6x6x6/mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best
Submitted job 60400044: 2-model_trained_from_6x6x6/mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best

Submitted: 2

======================================================================
2026-10-27 16:19 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again
$ vtriage list converged
Result: 11 folders

converged | mc_run_1vac/7-7Y/MC_Run_26Oct2026_09-23AM/T_0100K/Best_of_Best | -5579.50809197 eV
converged | mc_run_1vac/8-8Y/MC_Run_26Oct2026_09-27AM/T_0100K/Best_of_Best | -5576.95625713 eV
    slurm-60312274.out: DAV:  41    -0.575024350225E+04   -0.17380E+03   -0.46801E-03  9504   0.492E-02BRMIX: very serious problems
converged | mc_run_1vac/9-9Y/MC_Run_26Oct2026_09-30AM/T_0100K/Best_of_Best | -5576.21012861 eV
    slurm-60312275.out: DAV:  43    -0.661933486952E+04   -0.10437E+04   -0.49014E-05  6272   0.872E-03BRMIX: very serious problems
converged | mc_run_2vac/10-10Y/MC_Run_26Oct2026_10-29AM/T_0100K/Best_of_Best | -5559.30776934 eV
    slurm-60317841.out: DAV:  43    -0.571688560228E+04   -0.15870E+03   -0.10808E-03 10368   0.550E-02BRMIX: very serious problems
converged | mc_run_2vac/8-8Y/MC_Run_26Oct2026_10-22AM/T_0100K/Best_of_Best | -5561.60420866 eV
converged | mc_run_2vac/9-9Y/MC_Run_26Oct2026_10-26AM/T_0100K/Best_of_Best | -5561.18688908 eV
    slurm-60317851.out: DAV:  47    -0.594340753890E+04   -0.38295E+03   -0.26808E-03 10464   0.975E-02BRMIX: very serious problems
converged | mc_run_4vac/10-10Y/MC_Run_26Oct2026_11-15AM/T_0100K/Best_of_Best | -5528.44732129 eV
    slurm-60317913.out: DAV:  40    -0.605986543225E+04   -0.53300E+03   -0.91475E-06  5280   0.896E-03BRMIX: very serious problems
converged | mc_run_4vac/6-6Y/MC_Run_26Oct2026_11-01AM/T_0100K/Best_of_Best | -5533.10472457 eV
converged | mc_run_4vac/7-7Y/MC_Run_26Oct2026_11-05AM/T_0100K/Best_of_Best | -5533.03185095 eV
converged | mc_run_4vac/8-8Y/MC_Run_26Oct2026_11-08AM/T_0100K/Best_of_Best | -5530.93814997 eV
    slurm-60317922.out: DAV:  36    -0.563679185928E+04   -0.10741E+03   -0.39908E-04  8640   0.253E-02BRMIX: very serious problems
converged | mc_run_4vac/9-9Y/MC_Run_26Oct2026_11-12AM/T_0100K/Best_of_Best | -5530.21215086 eV

======================================================================
2026-10-27 16:20 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again
$ vtriage list crashed SCF diverged incomplete
Result: 13 folders

crashed | mc_run_1vac/2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
    slurm-60341693.out: [2026-10-27T13:51:45.304] error: *** STEP 60341693.0 ON nid004971 CANCELLED AT 2026-10-27T13:51:45 DUE TO TIME LIMIT ***
crashed | mc_run_1vac/3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
    slurm-60341695.out: [2026-10-27T13:56:54.176] error: *** STEP 60341695.0 ON nid004935 CANCELLED AT 2026-10-27T13:56:54 DUE TO TIME LIMIT ***
crashed | mc_run_1vac/4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
    slurm-60341701.out: [2026-10-27T15:46:59.317] error: *** STEP 60341701.0 ON nid007002 CANCELLED AT 2026-10-27T15:46:59 DUE TO TIME LIMIT ***
crashed | mc_run_1vac/5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
    slurm-60341704.out: [2026-10-27T15:47:30.064] error: *** STEP 60341704.0 ON nid005378 CANCELLED AT 2026-10-27T15:47:30 DUE TO TIME LIMIT ***
crashed | mc_run_1vac/6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
    slurm-60341706.out: [2026-10-27T17:30:30.068] error: *** STEP 60341706.0 ON nid004204 CANCELLED AT 2026-10-27T17:30:30 DUE TO TIME LIMIT ***
crashed | mc_run_2vac/2-2Y/MC_Run_26Oct2026_10-02AM/T_0100K/Best_of_Best
    slurm-60317842.out: [2026-10-26T17:13:06.992] error: *** STEP 60317842.0 ON nid004388 CANCELLED AT 2026-10-26T17:13:06 DUE TO TASK FAILURE ***
crashed | mc_run_2vac/3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
    slurm-60341747.out: [2026-10-27T17:30:30.085] error: *** STEP 60341747.0 ON nid004631 CANCELLED AT 2026-10-27T17:30:30 DUE TO TIME LIMIT ***
crashed | mc_run_2vac/4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
    slurm-60341748.out: [2026-10-27T18:47:54.086] error: *** STEP 60341748.0 ON nid004379 CANCELLED AT 2026-10-27T18:47:54 DUE TO TIME LIMIT ***
crashed | mc_run_2vac/5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
    slurm-60341749.out: [2026-10-27T18:48:56.016] error: *** STEP 60341749.0 ON nid006228 CANCELLED AT 2026-10-27T18:48:56 DUE TO TIME LIMIT ***
crashed | mc_run_2vac/6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
    slurm-60341750.out: [2026-10-27T19:41:16.139] error: *** STEP 60341750.0 ON nid004223 CANCELLED AT 2026-10-27T19:41:16 DUE TO TIME LIMIT ***
crashed | mc_run_2vac/7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
    slurm-60341751.out: [2026-10-27T19:43:18.017] error: *** STEP 60341751.0 ON nid004277 CANCELLED AT 2026-10-27T19:43:18 DUE TO TIME LIMIT ***
crashed | mc_run_4vac/2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
    slurm-60341875.out: [2026-10-27T20:01:16.318] error: *** STEP 60341875.0 ON nid004266 CANCELLED AT 2026-10-27T20:01:16 DUE TO TIME LIMIT ***
crashed | mc_run_4vac/3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
    slurm-60341876.out: [2026-10-27T20:01:16.315] error: *** STEP 60341876.0 ON nid005492 CANCELLED AT 2026-10-27T20:01:16 DUE TO TIME LIMIT ***

======================================================================
2026-10-27 16:21 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again
Result: finished

Jobs in queue: 5 of limit 100

Folders to submit: 13
  mc_run_1vac/2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_1vac/3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_1vac/4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_1vac/5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_1vac/6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_2vac/2-2Y/MC_Run_26Oct2026_10-02AM/T_0100K/Best_of_Best
  mc_run_2vac/3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_2vac/4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_2vac/5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_2vac/6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_2vac/7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_4vac/2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_run_4vac/3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 2: mc_run_1vac/2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_1vac/2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
Submitted job 60400186: mc_run_1vac/2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_1vac/3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_1vac/3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
Submitted job 60400187: mc_run_1vac/3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_1vac/4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_1vac/4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
Submitted job 60400188: mc_run_1vac/4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_1vac/5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_1vac/5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
Submitted job 60400189: mc_run_1vac/5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_1vac/6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_1vac/6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
Submitted job 60400191: mc_run_1vac/6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best
Archived as run 1: mc_run_2vac/2-2Y/MC_Run_26Oct2026_10-02AM/T_0100K/Best_of_Best
Submitted job 60400192: mc_run_2vac/2-2Y/MC_Run_26Oct2026_10-02AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_2vac/3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_2vac/3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
Submitted job 60400193: mc_run_2vac/3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_2vac/4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_2vac/4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
Submitted job 60400194: mc_run_2vac/4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_2vac/5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_2vac/5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
Submitted job 60400195: mc_run_2vac/5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_2vac/6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_2vac/6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
Submitted job 60400197: mc_run_2vac/6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_2vac/7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_2vac/7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
Submitted job 60400199: mc_run_2vac/7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_4vac/2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_4vac/2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
Submitted job 60400204: mc_run_4vac/2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best
Archived as run 2: mc_run_4vac/3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_run_4vac/3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best
Submitted job 60400236: mc_run_4vac/3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best

Submitted: 13

======================================================================
2026-10-27 16:21 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage list crashed SCF diverged incomplete
Result: 20 folders

crashed | mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60341922.out: [2026-10-27T16:51:11.936] error: *** STEP 60341922.0 ON nid005790 CANCELLED AT 2026-10-27T16:51:11 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60341923.out: [2026-10-27T16:51:42.149] error: *** STEP 60341923.0 ON nid004480 CANCELLED AT 2026-10-27T16:51:42 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60341927.out: [2026-10-27T17:16:43.058] error: *** STEP 60341927.0 ON nid004397 CANCELLED AT 2026-10-27T17:16:43 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60341930.out: [2026-10-27T17:17:13.022] error: *** STEP 60341930.0 ON nid004475 CANCELLED AT 2026-10-27T17:17:13 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60341931.out: [2026-10-27T17:48:42.705] error: *** STEP 60341931.0 ON nid004967 CANCELLED AT 2026-10-27T17:48:42 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60341932.out: [2026-10-27T17:49:42.721] error: *** STEP 60341932.0 ON nid007002 CANCELLED AT 2026-10-27T17:49:42 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
    slurm-60341933.out: [2026-10-27T18:40:13.098] error: *** STEP 60341933.0 ON nid004481 CANCELLED AT 2026-10-27T18:40:13 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60341934.out: [2026-10-27T18:40:43.696] error: *** STEP 60341934.0 ON nid005920 CANCELLED AT 2026-10-27T18:40:43 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
    slurm-60341937.out: [2026-10-27T19:13:50.088] error: *** STEP 60341937.0 ON nid005752 CANCELLED AT 2026-10-27T19:13:50 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
    slurm-60341940.out: [2026-10-27T19:15:25.049] error: *** STEP 60341940.0 ON nid004227 CANCELLED AT 2026-10-27T19:15:25 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
    slurm-60326406.out: [2026-10-27T00:12:24.094] error: *** STEP 60326406.0 ON nid004152 CANCELLED AT 2026-10-27T00:12:24 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
    slurm-60341941.out: [2026-10-27T20:04:53.264] error: *** STEP 60341941.0 ON nid004230 CANCELLED AT 2026-10-27T20:04:53 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
    slurm-60326783.out: [2026-10-27T03:45:37.139] error: *** STEP 60326783.0 ON nid005097 CANCELLED AT 2026-10-27T03:45:37 DUE TO TIME LIMIT ***
SCF diverged | mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
    slurm-60326722.out: [2026-10-27T00:20:07.104] error: *** JOB 60326722 ON nid005879 CANCELLED AT 2026-10-27T00:20:07 DUE TO TIME LIMIT ***
    last SCF energy -2.3e+10 eV, -5.37e+07 eV per atom, check POSCAR and POTCAR
crashed | mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
    slurm-60326723.out: [2026-10-27T01:04:38.952] error: *** STEP 60326723.0 ON nid004286 CANCELLED AT 2026-10-27T01:04:38 DUE TO TASK FAILURE ***
SCF diverged | mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
    slurm-60326724.out: [2026-10-27T02:05:46.113] error: *** STEP 60326724.0 ON nid006429 CANCELLED AT 2026-10-27T02:05:46 DUE TO TIME LIMIT ***
    last SCF energy -4.51e+10 eV, -1.05e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
    slurm-60326725.out: [2026-10-27T03:01:45.189] error: *** STEP 60326725.0 ON nid005357 CANCELLED AT 2026-10-27T03:01:45 DUE TO TIME LIMIT ***
    last SCF energy -4.39e+10 eV, -1.03e+08 eV per atom, check POSCAR and POTCAR
crashed | mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
    slurm-60326726.out: [2026-10-27T03:02:54.359] error: *** STEP 60326726.0 ON nid004224 CANCELLED AT 2026-10-27T03:02:54 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
    slurm-60326727.out: [2026-10-27T03:22:30.058] error: *** STEP 60326727.0 ON nid004989 CANCELLED AT 2026-10-27T03:22:30 DUE TO TIME LIMIT ***
SCF diverged | mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best
    slurm-60326728.out: [2026-10-27T03:22:30.063] error: *** STEP 60326728.0 ON nid005263 CANCELLED AT 2026-10-27T03:22:30 DUE TO TIME LIMIT ***
    last SCF energy -2.29e+06 eV, -5.35e+03 eV per atom, check POSCAR and POTCAR

======================================================================
2026-10-27 16:23 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage submit --group failed --root /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
Result: finished

Jobs in queue: 18 of limit 100
SCF diverged, last SCF energy -2.3e+10 eV, -5.37e+07 eV per atom, check POSCAR and POTCAR (use --force), skipped: mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
SCF diverged, last SCF energy -4.51e+10 eV, -1.05e+08 eV per atom, check POSCAR and POTCAR (use --force), skipped: mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
SCF diverged, last SCF energy -4.39e+10 eV, -1.03e+08 eV per atom, check POSCAR and POTCAR (use --force), skipped: mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
SCF diverged, last SCF energy -2.29e+06 eV, -5.35e+03 eV per atom, check POSCAR and POTCAR (use --force), skipped: mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Warning: same error as previous run (walltime). Change settings first: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best

Folders to submit: 16
  mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
  mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
  mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best  (CONTCAR to POSCAR)
Type yes to save each run and submit: Archived as run 3: mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Submitted job 60400300: mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Submitted job 60400301: mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Submitted job 60400307: mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Submitted job 60400308: mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Submitted job 60400310: mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Submitted job 60400342: mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Submitted job 60400343: mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Submitted job 60400346: mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Submitted job 60400348: mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Submitted job 60400349: mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
Submitted job 60400351: mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
Archived as run 3: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Submitted job 60400352: mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best
Archived as run 2: mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
Submitted job 60400353: mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
Submitted job 60400354: mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
Submitted job 60400356: mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best
Archived as run 1: mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
CONTCAR copied to POSCAR: mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best
Submitted job 60400357: mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best

Submitted: 16

======================================================================
2026-10-28 07:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 100: 100

Folders under .: 20
  converged: 19
  missing inputs: 1

======================================================================
2026-10-28 07:41 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/1-model_trained_from_4x4x4
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 10 folders

converged | mc_runs/1-10Y/MC_Run_22Oct2026_10-28AM/T_0100K/Best_of_Best | -5587.76234591 eV
converged | mc_runs/10-10Y/MC_Run_22Oct2026_11-35AM/T_0100K/Best_of_Best | -5587.76229245 eV
converged | mc_runs/2-2Y/MC_Run_22Oct2026_10-55AM/T_0100K/Best_of_Best | -5599.57957768 eV
converged | mc_runs/3-3Y/MC_Run_22Oct2026_11-00AM/T_0100K/Best_of_Best | -5598.90556955 eV
converged | mc_runs/4-4Y/MC_Run_22Oct2026_11-05AM/T_0100K/Best_of_Best | -5597.89158739 eV
converged | mc_runs/5-5Y/MC_Run_22Oct2026_11-10AM/T_0100K/Best_of_Best | -5595.37772343 eV
converged | mc_runs/6-6Y/MC_Run_22Oct2026_11-15AM/T_0100K/Best_of_Best | -5594.42438105 eV
converged | mc_runs/7-7Y/MC_Run_23Oct2026_10-51AM/T_0100K/Best_of_Best | -5593.97627253 eV
converged | mc_runs/8-8Y/MC_Run_22Oct2026_11-25AM/T_0100K/Best_of_Best | -5590.47930228 eV
converged | mc_runs/9-9Y/MC_Run_22Oct2026_11-30AM/T_0100K/Best_of_Best | -5590.28180853 eV

======================================================================
2026-10-28 07:42 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/1-W10-0vac/2-model_trained_from_6x6x6
$ vtriage list converged crashed after reaching accuracy SCF not converged ionic not converged crashed SCF diverged incomplete running or pending not submitted missing inputs
Result: 10 folders

missing inputs | .
    missing: POSCAR, POTCAR
converged | mc_runs/10-10Y/MC_Run_22Oct2026_03-10PM/T_0100K/Best_of_Best | -5587.48648865 eV
converged | mc_runs/2-2Y/MC_Run_22Oct2026_11-55AM/T_0100K/Best_of_Best | -5599.64431065 eV
converged | mc_runs/3-3Y/MC_Run_22Oct2026_11-57AM/T_0100K/Best_of_Best | -5598.89761407 eV
converged | mc_runs/4-4Y/MC_Run_22Oct2026_11-59AM/T_0100K/Best_of_Best | -5597.89176512 eV
converged | mc_runs/5-5Y/MC_Run_22Oct2026_12-00PM/T_0100K/Best_of_Best | -5595.43980543 eV
converged | mc_runs/6-6Y/MC_Run_22Oct2026_12-02PM/T_0100K/Best_of_Best | -5594.21664938 eV
converged | mc_runs/7-7Y/MC_Run_23Oct2026_10-50AM/T_0100K/Best_of_Best | -5593.39705707 eV
converged | mc_runs/8-8Y/MC_Run_22Oct2026_12-06PM/T_0100K/Best_of_Best | -5590.25872811 eV
converged | mc_runs/9-9Y/MC_Run_22Oct2026_12-07PM/T_0100K/Best_of_Best | -5589.97591028 eV

======================================================================
2026-10-28 07:43 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again
$ vtriage list crashed SCF diverged incomplete
Result: 5 folders

crashed | mc_run_1vac/10-10Y/MC_Run_26Oct2026_09-33AM/T_0100K/Best_of_Best
    slurm-60365755.out: [2026-10-28T00:09:52.145] error: *** STEP 60365755.0 ON nid006141 CANCELLED AT 2026-10-28T00:09:52 DUE TO TIME LIMIT ***
crashed | mc_run_2vac/2-2Y/MC_Run_26Oct2026_10-02AM/T_0100K/Best_of_Best
    slurm-60400192.out: [2026-10-28T02:11:34.484] error: *** STEP 60400192.0 ON nid005776 CANCELLED AT 2026-10-28T02:11:34 DUE TO TASK FAILURE ***
crashed | mc_run_2vac/6-6Y/MC_Run_26Oct2026_10-16AM/T_0100K/Best_of_Best
    slurm-60400197.out: [2026-10-28T08:51:50.095] error: *** STEP 60400197.0 ON nid004204 CANCELLED AT 2026-10-28T08:51:50 DUE TO TIME LIMIT ***
crashed | mc_run_4vac/4-4Y/MC_Run_26Oct2026_10-55AM/T_0100K/Best_of_Best
    slurm-60341878.out: [2026-10-27T20:21:19.120] error: *** STEP 60341878.0 ON nid005214 CANCELLED AT 2026-10-27T20:21:19 DUE TO TIME LIMIT ***
crashed | mc_run_4vac/5-5Y/MC_Run_26Oct2026_10-58AM/T_0100K/Best_of_Best
    slurm-60341879.out: [2026-10-27T20:21:19.119] error: *** STEP 60341879.0 ON nid005242 CANCELLED AT 2026-10-27T20:21:19 DUE TO TIME LIMIT ***

======================================================================
2026-10-28 07:46 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/3-model_trained_on_5x5x5_again
$ vtriage list converged
Result: 22 folders

converged | mc_run_1vac/2-2Y/MC_Run_26Oct2026_09-07AM/T_0100K/Best_of_Best | -5583.99281102 eV
converged | mc_run_1vac/3-3Y/MC_Run_26Oct2026_09-10AM/T_0100K/Best_of_Best | -5583.45650606 eV
converged | mc_run_1vac/4-4Y/MC_Run_26Oct2026_09-13AM/T_0100K/Best_of_Best | -5582.34141341 eV
converged | mc_run_1vac/5-5Y/MC_Run_26Oct2026_09-17AM/T_0100K/Best_of_Best | -5580.3601293 eV
converged | mc_run_1vac/6-6Y/MC_Run_26Oct2026_09-20AM/T_0100K/Best_of_Best | -5579.31888066 eV
converged | mc_run_1vac/7-7Y/MC_Run_26Oct2026_09-23AM/T_0100K/Best_of_Best | -5579.50809197 eV
converged | mc_run_1vac/8-8Y/MC_Run_26Oct2026_09-27AM/T_0100K/Best_of_Best | -5576.95625713 eV
    slurm-60312274.out: DAV:  41    -0.575024350225E+04   -0.17380E+03   -0.46801E-03  9504   0.492E-02BRMIX: very serious problems
converged | mc_run_1vac/9-9Y/MC_Run_26Oct2026_09-30AM/T_0100K/Best_of_Best | -5576.21012861 eV
    slurm-60312275.out: DAV:  43    -0.661933486952E+04   -0.10437E+04   -0.49014E-05  6272   0.872E-03BRMIX: very serious problems
converged | mc_run_2vac/10-10Y/MC_Run_26Oct2026_10-29AM/T_0100K/Best_of_Best | -5559.30776934 eV
    slurm-60317841.out: DAV:  43    -0.571688560228E+04   -0.15870E+03   -0.10808E-03 10368   0.550E-02BRMIX: very serious problems
converged | mc_run_2vac/3-3Y/MC_Run_26Oct2026_10-06AM/T_0100K/Best_of_Best | -5567.68414827 eV
converged | mc_run_2vac/4-4Y/MC_Run_26Oct2026_10-09AM/T_0100K/Best_of_Best | -5566.61024284 eV
converged | mc_run_2vac/5-5Y/MC_Run_26Oct2026_10-12AM/T_0100K/Best_of_Best | -5564.84649785 eV
converged | mc_run_2vac/7-7Y/MC_Run_26Oct2026_10-19AM/T_0100K/Best_of_Best | -5563.19253329 eV
converged | mc_run_2vac/8-8Y/MC_Run_26Oct2026_10-22AM/T_0100K/Best_of_Best | -5561.60420866 eV
converged | mc_run_2vac/9-9Y/MC_Run_26Oct2026_10-26AM/T_0100K/Best_of_Best | -5561.18688908 eV
    slurm-60317851.out: DAV:  47    -0.594340753890E+04   -0.38295E+03   -0.26808E-03 10464   0.975E-02BRMIX: very serious problems
converged | mc_run_4vac/10-10Y/MC_Run_26Oct2026_11-15AM/T_0100K/Best_of_Best | -5528.44732129 eV
    slurm-60317913.out: DAV:  40    -0.605986543225E+04   -0.53300E+03   -0.91475E-06  5280   0.896E-03BRMIX: very serious problems
converged | mc_run_4vac/2-2Y/MC_Run_26Oct2026_10-48AM/T_0100K/Best_of_Best | -5535.60540422 eV
converged | mc_run_4vac/3-3Y/MC_Run_26Oct2026_10-51AM/T_0100K/Best_of_Best | -5535.36635962 eV
converged | mc_run_4vac/6-6Y/MC_Run_26Oct2026_11-01AM/T_0100K/Best_of_Best | -5533.10472457 eV
converged | mc_run_4vac/7-7Y/MC_Run_26Oct2026_11-05AM/T_0100K/Best_of_Best | -5533.03185095 eV
converged | mc_run_4vac/8-8Y/MC_Run_26Oct2026_11-08AM/T_0100K/Best_of_Best | -5530.93814997 eV
    slurm-60317922.out: DAV:  36    -0.563679185928E+04   -0.10741E+03   -0.39908E-04  8640   0.253E-02BRMIX: very serious problems
converged | mc_run_4vac/9-9Y/MC_Run_26Oct2026_11-12AM/T_0100K/Best_of_Best | -5530.21215086 eV

======================================================================
2026-10-28 08:02 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage list converged
Result: 10 folders

converged | mc_runs_1vac/10-10Y/MC_Run_22Oct2026_03-57PM/T_0100K/Best_of_Best | -5573.15889818 eV
converged | mc_runs_1vac/6-6Y/MC_Run_22Oct2026_03-44PM/T_0100K/Best_of_Best | -5578.38325344 eV
converged | mc_runs_1vac/8-8Y/MC_Run_22Oct2026_03-51PM/T_0100K/Best_of_Best | -5575.87601301 eV
converged | mc_runs_1vac/9-9Y/MC_Run_22Oct2026_03-54PM/T_0100K/Best_of_Best | -5575.4718731 eV
converged | mc_runs_2vac/7-7Y/MC_Run_22Oct2026_04-18PM/T_0100K/Best_of_Best | -5562.6760141 eV
converged | mc_runs_2vac/8-8Y/MC_Run_22Oct2026_04-21PM/T_0100K/Best_of_Best | -5560.29922815 eV
converged | mc_runs_2vac/9-9Y/MC_Run_22Oct2026_04-24PM/T_0100K/Best_of_Best | -5559.91199936 eV
converged | mc_runs_4vac/10-10Y/MC_Run_22Oct2026_04-58PM/T_0100K/Best_of_Best | -5528.01851002 eV
converged | mc_runs_4vac/7-7Y/MC_Run_22Oct2026_04-48PM/T_0100K/Best_of_Best | -5532.23397378 eV
converged | mc_runs_4vac/8-8Y/MC_Run_22Oct2026_04-51PM/T_0100K/Best_of_Best | -5529.8749162 eV

======================================================================
2026-10-28 08:08 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage list crashed SCF diverged incomplete
Result: 17 folders

crashed | mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60400300.out: [2026-10-28T06:54:18.608] error: *** STEP 60400300.0 ON nid004267 CANCELLED AT 2026-10-28T06:54:18 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60400301.out: Inconsistent Bravais lattice types found for crystalline and
crashed | mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60400307.out: [2026-10-28T07:38:36.044] error: *** STEP 60400307.0 ON nid006033 CANCELLED AT 2026-10-28T07:38:36 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60400308.out: [2026-10-28T08:26:36.340] error: *** STEP 60400308.0 ON nid004602 CANCELLED AT 2026-10-28T08:26:36 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60400310.out: [2026-10-28T08:27:05.017] error: *** STEP 60400310.0 ON nid004967 CANCELLED AT 2026-10-28T08:27:05 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60400342.out: [2026-10-28T09:06:41.105] error: *** STEP 60400342.0 ON nid004512 CANCELLED AT 2026-10-28T09:06:41 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
    slurm-60400343.out: [2026-10-28T09:06:41.109] error: *** JOB 60400343 ON nid004599 CANCELLED AT 2026-10-28T09:06:41 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60400346.out: [2026-10-28T09:32:04.338] error: *** STEP 60400346.0 ON nid005505 CANCELLED AT 2026-10-28T09:32:04 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
    slurm-60400348.out: [2026-10-28T09:35:09.980] error: *** STEP 60400348.0 ON nid004259 CANCELLED AT 2026-10-28T09:35:09 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
    slurm-60400349.out: [2026-10-28T10:10:16.475] error: *** STEP 60400349.0 ON nid004168 CANCELLED AT 2026-10-28T10:10:16 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
    slurm-60400351.out: [2026-10-28T10:10:16.473] error: *** STEP 60400351.0 ON nid006492 CANCELLED AT 2026-10-28T10:10:16 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
    slurm-60400353.out: [2026-10-28T10:39:57.091] error: *** STEP 60400353.0 ON nid004927 CANCELLED AT 2026-10-28T10:39:57 DUE TO TIME LIMIT ***
SCF diverged | mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
    slurm-60326722.out: [2026-10-27T00:20:07.104] error: *** JOB 60326722 ON nid005879 CANCELLED AT 2026-10-27T00:20:07 DUE TO TIME LIMIT ***
    last SCF energy -2.3e+10 eV, -5.37e+07 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
    slurm-60400354.out: [2026-10-28T11:12:36.066] error: *** STEP 60400354.0 ON nid004341 CANCELLED AT 2026-10-28T11:12:36 DUE TO TIME LIMIT ***
    last SCF energy -2.16e+09 eV, -5.04e+06 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
    slurm-60326724.out: [2026-10-27T02:05:46.113] error: *** STEP 60326724.0 ON nid006429 CANCELLED AT 2026-10-27T02:05:46 DUE TO TIME LIMIT ***
    last SCF energy -4.51e+10 eV, -1.05e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
    slurm-60326725.out: [2026-10-27T03:01:45.189] error: *** STEP 60326725.0 ON nid005357 CANCELLED AT 2026-10-27T03:01:45 DUE TO TIME LIMIT ***
    last SCF energy -4.39e+10 eV, -1.03e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best
    slurm-60326728.out: [2026-10-27T03:22:30.063] error: *** STEP 60326728.0 ON nid005263 CANCELLED AT 2026-10-27T03:22:30 DUE TO TIME LIMIT ***
    last SCF energy -2.29e+06 eV, -5.35e+03 eV per atom, check POSCAR and POTCAR

======================================================================
2026-10-28 09:17 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage status
Result: checked

Jobs from this folder: 0

All my jobs in the queue: 0
  free slots under limit 100: 100

Folders under .: 9
  converged: 4
  crashed: 5

======================================================================
2026-10-28 09:17 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6/mc_runs_1vac
$ vtriage list crashed SCF diverged incomplete
Result: 5 folders

crashed | 2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60400300.out: [2026-10-28T06:54:18.608] error: *** STEP 60400300.0 ON nid004267 CANCELLED AT 2026-10-28T06:54:18 DUE TO TIME LIMIT ***
crashed | 3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60400301.out: Inconsistent Bravais lattice types found for crystalline and
crashed | 4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60400307.out: [2026-10-28T07:38:36.044] error: *** STEP 60400307.0 ON nid006033 CANCELLED AT 2026-10-28T07:38:36 DUE TO TIME LIMIT ***
crashed | 5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60400308.out: [2026-10-28T08:26:36.340] error: *** STEP 60400308.0 ON nid004602 CANCELLED AT 2026-10-28T08:26:36 DUE TO TIME LIMIT ***
crashed | 7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60400310.out: [2026-10-28T08:27:05.017] error: *** STEP 60400310.0 ON nid004967 CANCELLED AT 2026-10-28T08:27:05 DUE TO TIME LIMIT ***

======================================================================
2026-10-28 09:20 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage list crashed SCF diverged incomplete
Result: 17 folders

crashed | mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60400300.out: [2026-10-28T06:54:18.608] error: *** STEP 60400300.0 ON nid004267 CANCELLED AT 2026-10-28T06:54:18 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60400301.out: Inconsistent Bravais lattice types found for crystalline and
crashed | mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60400307.out: [2026-10-28T07:38:36.044] error: *** STEP 60400307.0 ON nid006033 CANCELLED AT 2026-10-28T07:38:36 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60400308.out: [2026-10-28T08:26:36.340] error: *** STEP 60400308.0 ON nid004602 CANCELLED AT 2026-10-28T08:26:36 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60400310.out: [2026-10-28T08:27:05.017] error: *** STEP 60400310.0 ON nid004967 CANCELLED AT 2026-10-28T08:27:05 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60400342.out: [2026-10-28T09:06:41.105] error: *** STEP 60400342.0 ON nid004512 CANCELLED AT 2026-10-28T09:06:41 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
    slurm-60400343.out: [2026-10-28T09:06:41.109] error: *** JOB 60400343 ON nid004599 CANCELLED AT 2026-10-28T09:06:41 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60400346.out: [2026-10-28T09:32:04.338] error: *** STEP 60400346.0 ON nid005505 CANCELLED AT 2026-10-28T09:32:04 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
    slurm-60400348.out: [2026-10-28T09:35:09.980] error: *** STEP 60400348.0 ON nid004259 CANCELLED AT 2026-10-28T09:35:09 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
    slurm-60400349.out: [2026-10-28T10:10:16.475] error: *** STEP 60400349.0 ON nid004168 CANCELLED AT 2026-10-28T10:10:16 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
    slurm-60400351.out: [2026-10-28T10:10:16.473] error: *** STEP 60400351.0 ON nid006492 CANCELLED AT 2026-10-28T10:10:16 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
    slurm-60400353.out: [2026-10-28T10:39:57.091] error: *** STEP 60400353.0 ON nid004927 CANCELLED AT 2026-10-28T10:39:57 DUE TO TIME LIMIT ***
SCF diverged | mc_runs_4vac/3-3Y/MC_Run_22Oct2026_04-34PM/T_0100K/Best_of_Best
    slurm-60326722.out: [2026-10-27T00:20:07.104] error: *** JOB 60326722 ON nid005879 CANCELLED AT 2026-10-27T00:20:07 DUE TO TIME LIMIT ***
    last SCF energy -2.3e+10 eV, -5.37e+07 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/4-4Y/MC_Run_22Oct2026_04-38PM/T_0100K/Best_of_Best
    slurm-60400354.out: [2026-10-28T11:12:36.066] error: *** STEP 60400354.0 ON nid004341 CANCELLED AT 2026-10-28T11:12:36 DUE TO TIME LIMIT ***
    last SCF energy -2.16e+09 eV, -5.04e+06 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/5-5Y/MC_Run_22Oct2026_04-41PM/T_0100K/Best_of_Best
    slurm-60326724.out: [2026-10-27T02:05:46.113] error: *** STEP 60326724.0 ON nid006429 CANCELLED AT 2026-10-27T02:05:46 DUE TO TIME LIMIT ***
    last SCF energy -4.51e+10 eV, -1.05e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/6-6Y/MC_Run_22Oct2026_04-44PM/T_0100K/Best_of_Best
    slurm-60326725.out: [2026-10-27T03:01:45.189] error: *** STEP 60326725.0 ON nid005357 CANCELLED AT 2026-10-27T03:01:45 DUE TO TIME LIMIT ***
    last SCF energy -4.39e+10 eV, -1.03e+08 eV per atom, check POSCAR and POTCAR
SCF diverged | mc_runs_4vac/9-9Y/MC_Run_22Oct2026_04-55PM/T_0100K/Best_of_Best
    slurm-60326728.out: [2026-10-27T03:22:30.063] error: *** STEP 60326728.0 ON nid005263 CANCELLED AT 2026-10-27T03:22:30 DUE TO TIME LIMIT ***
    last SCF energy -2.29e+06 eV, -5.35e+03 eV per atom, check POSCAR and POTCAR

======================================================================
2026-10-28 09:21 | perlmutter | /pscratch/sd/g/garora/Villanova/mecxtrain_and_mcagent/2-W10-4vac-1vac-2vac/2-model_trained_on_6x6x6
$ vtriage list crashed
Result: 12 folders

crashed | mc_runs_1vac/2-2Y/MC_Run_22Oct2026_03-31PM/T_0100K/Best_of_Best
    slurm-60400300.out: [2026-10-28T06:54:18.608] error: *** STEP 60400300.0 ON nid004267 CANCELLED AT 2026-10-28T06:54:18 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/3-3Y/MC_Run_22Oct2026_03-34PM/T_0100K/Best_of_Best
    slurm-60400301.out: Inconsistent Bravais lattice types found for crystalline and
crashed | mc_runs_1vac/4-4Y/MC_Run_22Oct2026_03-37PM/T_0100K/Best_of_Best
    slurm-60400307.out: [2026-10-28T07:38:36.044] error: *** STEP 60400307.0 ON nid006033 CANCELLED AT 2026-10-28T07:38:36 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/5-5Y/MC_Run_22Oct2026_03-41PM/T_0100K/Best_of_Best
    slurm-60400308.out: [2026-10-28T08:26:36.340] error: *** STEP 60400308.0 ON nid004602 CANCELLED AT 2026-10-28T08:26:36 DUE TO TIME LIMIT ***
crashed | mc_runs_1vac/7-7Y/MC_Run_22Oct2026_03-47PM/T_0100K/Best_of_Best
    slurm-60400310.out: [2026-10-28T08:27:05.017] error: *** STEP 60400310.0 ON nid004967 CANCELLED AT 2026-10-28T08:27:05 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/10-10Y/MC_Run_22Oct2026_04-28PM/T_0100K/Best_of_Best
    slurm-60400342.out: [2026-10-28T09:06:41.105] error: *** STEP 60400342.0 ON nid004512 CANCELLED AT 2026-10-28T09:06:41 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/2-2Y/MC_Run_22Oct2026_04-01PM/T_0100K/Best_of_Best
    slurm-60400343.out: [2026-10-28T09:06:41.109] error: *** JOB 60400343 ON nid004599 CANCELLED AT 2026-10-28T09:06:41 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/3-3Y/MC_Run_22Oct2026_04-04PM/T_0100K/Best_of_Best
    slurm-60400346.out: [2026-10-28T09:32:04.338] error: *** STEP 60400346.0 ON nid005505 CANCELLED AT 2026-10-28T09:32:04 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/4-4Y/MC_Run_22Oct2026_04-07PM/T_0100K/Best_of_Best
    slurm-60400348.out: [2026-10-28T09:35:09.980] error: *** STEP 60400348.0 ON nid004259 CANCELLED AT 2026-10-28T09:35:09 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/5-5Y/MC_Run_22Oct2026_04-11PM/T_0100K/Best_of_Best
    slurm-60400349.out: [2026-10-28T10:10:16.475] error: *** STEP 60400349.0 ON nid004168 CANCELLED AT 2026-10-28T10:10:16 DUE TO TIME LIMIT ***
crashed | mc_runs_2vac/6-6Y/MC_Run_22Oct2026_04-14PM/T_0100K/Best_of_Best
    slurm-60400351.out: [2026-10-28T10:10:16.473] error: *** STEP 60400351.0 ON nid006492 CANCELLED AT 2026-10-28T10:10:16 DUE TO TIME LIMIT ***
crashed | mc_runs_4vac/2-2Y/MC_Run_22Oct2026_04-31PM/T_0100K/Best_of_Best
    slurm-60400353.out: [2026-10-28T10:39:57.091] error: *** STEP 60400353.0 ON nid004927 CANCELLED AT 2026-10-28T10:39:57 DUE TO TIME LIMIT ***

