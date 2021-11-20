# Usage
```go
package main
import (
	"fmt"
	"github.com/wirekang/vkmap"
)

func main(){
	fmt.Println(vkmap.Map[0x08].VK) // VK_BACK
	fmt.Println(vkmap.Map[0x09].Description) // TAB key
}
```