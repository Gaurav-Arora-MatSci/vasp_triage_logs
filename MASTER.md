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

