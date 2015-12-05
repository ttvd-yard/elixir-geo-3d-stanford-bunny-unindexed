# elixir-geo-3d-stanford-bunny-unindexed

Stanford bunny model. Unindexed data.

## Usage
Add dependency in your mix.exs file:
```
def deps do
  [{:geo_3d_stanford_bunny_unindexed, "~> 0.1"}]
end
```

## Other
* For indexed version, please see:
  * [elixir-geo-3d-stanford-bunny](https://github.com/ttvd/elixir-geo-3d-stanford-bunny)

## Functions
* Get unindexed data:
```
Geo3d.StanfordBunnyUnindexed.vertices :: [{Geo3d.point3, Geo3d.point3, Geo3d.point3}]
```

## Dependencies
* [elixir-geo-3d-utils](https://github.com/ttvd/elixir-geo-3d-utils)
* [elixir-geo-3d-types](https://github.com/ttvd/elixir-geo-3d-types)

## License

* Copyright Mykola Konyk, 2015
* Distributed under the [MS-RL License.](http://opensource.org/licenses/MS-RL)
* **To further explain the license:**
  * **You cannot re-license any files in this project.**
  * **That is, they must remain under the [MS-RL license.](http://opensource.org/licenses/MS-RL)**
  * **Any other files you add to this project can be under any license you want.**
  * **You cannot use any of this code in a GPL project.**
  * Otherwise you are free to do pretty much anything you want with this code.