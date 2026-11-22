# esimv1-earth2100

The planet to 2100 under several assumptions about emissions, with the people and the
thresholds on each path. Each variant is an assumption, never a forecast. Shown at
[/anselm/planet-2100](https://esimv1.exe.xyz/anselm/planet-2100).

- `planet-2100/` is the project: description, the resolved manifest, the variants, the
  README a lay reader starts from.
- It has no record of its own. The tables it reads (the tipping elements, the wild cards,
  the global records) are shared and live in the engine, `esimv1-core`, `data/events/`
  and the catalog.
- Its manifest as written is `manifests/p4-planet-people.toml` in `esimv1-core`, which
  is also a rung of the engine's regression ladder.

## Run it

This is content for [esimv1](https://github.com/anselm/esimv1): the description, the
manifest, the record the model is read against, and the page. It holds no code. With a
built [esimv1-core](https://github.com/anselm/esimv1-core) (0.3.0 or newer):

```
ESIM_ROOT=/path/to/esimv1-core /path/to/esimv1-core/target/release/esim project run ./<project folder> --variant <name>
```

Runs land in the project folder's `runs/`, which is not in git: a run is rebuilt from its
manifest and seed. The hub shows this scenario at the addresses given above by keeping a
clone of this repository and linking the project folders into its `projects/`.

Free and open source, MIT. The records in `data/events/` keep their publishers' terms,
which each folder's README names.
