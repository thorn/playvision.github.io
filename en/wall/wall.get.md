---
title: wall.get
---
Returns a list of posts on the user's wall

### Accepted parameters ###

**user_id**: the user ID to return wall posts of

###Example request###

> http://**domain**/v1/wall.get?user_id=100

### Returned data: ###
<pre>
    <code>
        {
            "response": {
                "count": 4,
                "items": [
                    {
                        "id": 84,
                        "text": "няшный руби:kissing_closed_eyes:\n",
                        "from_id": 131,
                        "to_id": 100,
                        "date": 1406291471,
                        "likes": {
                            "count": 0
                        }
                    },
                    {
                        "id": 81,
                        "text": "test",
                        "from_id": 100,
                        "to_id": 100,
                        "date": 1406118145,
                        "likes": {
                            "count": 2
                        }
                    },
                    {
                        "id": 62,
                        "text": "тест\n\n",
                        "from_id": 100,
                        "to_id": 100,
                        "date": 1404902317,
                        "likes": {
                            "count": 0
                        }
                    },
                    {
                        "id": 32,
                        "text": ":stuck_out_tongue::yum::trollface::neckbeard::frowning::confused::angry::satisfied:",
                        "from_id": 131,
                        "to_id": 100,
                        "date": 1403793210,
                        "likes": {
                            "count": 0
                        }
                    }
                ]
            }
        }
    </code>

</pre>
