#Ships

[![Code Climate](https://codeclimate.com/repos/54dc91786956802bb5001ccf/badges/d0ea965b5160d60f5002/gpa.svg)](https://codeclimate.com/repos/54dc91786956802bb5001ccf/feed)

| Responsibility       | Collaborators |
|----------------------|:-------------:|
| Be hit?              | Players, Board|
| Sink                 | Board         |
| Be placed            | Board, Players|

#Board
possibility: (class Primary Grid << Tracking Grid)

| Responsibility       | Collaborators |
|----------------------|:-------------:|
| Record ship          | Ship          |
| Record shots         | Player        |

#Player

| Responsibility       | Collaborators |
|----------------------|:-------------:|
| Shoot                | Board         |
| Place ship           | Ship, Board   |

#GameHandler

| Responsibility       | Collaborators |
|----------------------|:-------------:|
| Set Board            | Players	   |
| Start game           | Board, Players|
| Decide turn          | Players       |
| Finish game          | Players, Board|
| Save game            | Board         |

