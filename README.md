# ourl

This is the ourl tool from https://github.com/j3ssie/go-auxs/tree/master/ourl . 

I just  want to get all the wayback urls.

Code changes
from 
```
fmt.Println(result[2])
```

to 

```
fmt.Printf("https://web.archive.org/web/%sid_/%s\n", result[1], result[2])
```

## Credits

Thanks to jessie, Tindild.
