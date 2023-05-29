# hashi-vault-barrier-aes-gcm

> 💡 Hashicorp vault [library](https://github.com/hashicorp/vault) aes gcm. SecurityBarrier implements github.com/hashicorp/vault/sdk/logical storage interface

```go
// Storage is the way that logical backends are able read/write data.
type Storage interface {
	List(context.Context, string) ([]string, error)
	Get(context.Context, string) (*StorageEntry, error)
	Put(context.Context, *StorageEntry) error
	Delete(context.Context, string) error
}
```
