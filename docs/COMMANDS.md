# ARC-Room Commands

Commands are entered in the bottom console. A leading slash is optional.

## Help

```txt
/help
```

Prints available commands.

## Spawn primitives

```txt
/summon cube
/summon cube scale=2 at=0,1,0
/summon marker scale=1 at=2,1,-2
```

Spawns built-in primitive test objects.

## Selection

```txt
/list
/select object_id
/select first
```

## Transform

```txt
/scale object_id 2
/move object_id 0 1 4
/rotate object_id y 90
/tp object_id 0 1 4
```

Rotation is in degrees. Internally, the scene stores radians.

## Lifecycle

```txt
/despawn object_id
/despawn selected
/despawn all
/kill object_id
/duplicate object_id
```

## Visibility and tags

```txt
/tag object_id furniture
/hide object_id
/show object_id
```

## Scene

```txt
/export json
/save
/load
/reset
/grid on
/grid off
/hud
```

`/save` stores the scene in localStorage. `/export json` downloads the full scene state.
