# Textile Repository 
A utility, wrapper class to query your collection in threadsDB of Textile (IPFS).

Textile repository class is a wrapper class that will help you to give you always the Model class with the generic interface.

When you develop with [Textile](https://textile.io) ThreadsDB, this will be very helpfull.


```typescript
export interface ISearch extends Model {
    name: string;
    blob: any;
}

const repo = new Repository<ISearch>(searchCollectionName, db, threadId);
repo.findById(id);
```
