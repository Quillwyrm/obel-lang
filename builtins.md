; predicates
(nil? x)
(bool? x)
(num? x)
(int? x)
(float? x)
(str? x)
(vec? x)
(map? x)
(fn? x)
;(list? x) ;later when i have quote and meta stuff

; shared vec/map
(len x)
(copy x)
(clear x)

; vector
(push v value...)
(pop v)
(insert v i value)
(remove v i)
(slice v start count)

; map
(keys m)
(vals m)
(pairs m)
(merge map...)

; higher-order
(each f coll)
(map f coll)
(filter pred coll)
(reduce f init coll)
