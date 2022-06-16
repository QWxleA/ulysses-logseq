- [[I Telemachus]]
- [[II Nestor]]
- [[III Proteus]]
- [[IV Calypso]]
- [[V Lotus Eaters]]
- [[VI Hades]]
- [[VII Aeolus]]
- [[VIII Lestrygonians]]
- [[IX Scylla and Charybdis]]
- [[X Wandering Rocks]]
- [[XI Sirens]]
- [[XII Cyclops]]
- [[XIII Nausicaa]]
- [[XIV Oxen of the Sun]]
- [[XV Circe]]
- [[XVI Eumaeus]]
- [[XVII Ithaca]]
- [[XVIII Penelope]]
- [[About]]
- [[Notes]]
- [[mxene review paper/aaaa]]
- [[Mxene Review Paper/aaaa]]
- [[mxene review paper/aaaa/bbbb]]
- #+BEGIN_QUERY
   {:title [:b"Open Topics MXene review paper"]
   :query [:find (pull ?b [*])
   :where
    (page-ref ?b "open topics")
    [?b :block/page ?p]
    [(clojure.string/includes? ?p "aa")]
    ;;[(clojure.string/includes? ?p "mxene review paper")]
   ]}
   #+END_QUERY