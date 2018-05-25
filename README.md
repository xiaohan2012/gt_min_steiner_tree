# gt_min_steiner_tree

minimum steiner tree algorithm for `graph_tool`

# usage

    from minimum_steiner_tree import min_steiner_tree
    g = <graph_tool.Graph object>
    obs = <list of ints>  # the terminals
    t = min_steiner_tree(g, obs)  # returns a tree of type graph_tool.Graph
