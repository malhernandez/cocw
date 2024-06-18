# CoreWeave CloudOps Notes

## Kubernetes

Log into cluster
```# tl```

Get cluster context 
```# k config get-contexts```

change and select namespace
```# k ns```


Get login status
```# tsh status```

logout 
``` # tsh logout```

Get Pods
```# kgp -o wide```

Get Deployments
```# k get deployments```

switch context
```# kctx```


SSH to a node
``` # tsh ssh acc@IP```


## Git

Add changes to the commit
```# git add .```

Commit changes
```# git commit -m "creating cw notes"```


Amend changes
```# git commit --amend```


Push changes to repo
```# git push```