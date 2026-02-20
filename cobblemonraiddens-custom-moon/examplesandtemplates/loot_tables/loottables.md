```
{
    "type": "minecraft:chest",
    "pools": [
        {
            "rolls": 1,
            "entries": [
                {
                    "type": "minecraft:item",
                    "functions": [
                        {
                            "add": false,
                            "count": {
                                "type": "minecraft:uniform",
                                "min":5.0,
                                "max":10.0
                            },
                            "function": "minecraft:set_count"
                        }
                    ],
                    "name": "modname:random_count_item",
                    "weight":20.0
                },
                {
                    "type": "minecraft:item",
                    "functions": [
                        {
                            "add": false,
                            "count": 1.0,
                            "function": "minecraft:set_count"
                        }
                    ],
                    "name": "modname:set_count_item",
                    "weight":20.0
                }
            ]
        },
        {
            "rolls": 1,
            "entries": [
                {
                    "type": "minecraft:item",
                    "functions": [
                        {
                            "add": false,
                            "count": {
                                "type": "minecraft:uniform",
                                "min":5.0,
                                "max":10.0
                            },
                            "function": "minecraft:set_count"
                        }
                    ],
                    "name": "modname:random_count_item",
                    "weight": 20.0
                }
            ]
        },
        {
            "rolls": 1,
            "entries": [
                {
                    "type": "minecraft:item",
                    "functions": [
                        {
                            "add": false,
                            "count": 1.0,
                            "function": "minecraft:set_count"
                        }
                    ],
                    "name": "modname:set_count_item",
                    "weight": 20.0
                }
            ]
        }
    ]
}
```