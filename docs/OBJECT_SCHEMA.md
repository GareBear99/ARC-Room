# ARC-Room Object Schema

Scene exports are designed to be readable by humans and AI agents.

```json
{
  "app": "ARC-Room Tactical Mesh Object Intake Lab",
  "version": "0.1.0",
  "time": "2026-05-13T00:00:00.000Z",
  "room": {
    "units": "meters",
    "gridSize": 1,
    "bounds": [40, 10, 40]
  },
  "objects": [
    {
      "id": "cube_001",
      "name": "cube",
      "sourceFile": "cube",
      "type": "uploaded-object",
      "position": [0, 1, 0],
      "rotation": [0, 0, 0],
      "scale": [1, 1, 1],
      "tags": ["sample"],
      "visible": true,
      "locked": false,
      "bounds": {
        "min": [-1, 0, -1],
        "max": [1, 2, 1],
        "size": [2, 2, 2]
      },
      "mesh": {
        "vertices": [],
        "faces": []
      }
    }
  ],
  "receipts": []
}
```

## Design goals

- Keep object IDs stable.
- Store transforms separately from raw geometry.
- Keep bounds available for AI reasoning.
- Preserve command receipts for replay, audit, and later ARC/OmniBinary integration.
