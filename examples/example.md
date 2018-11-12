# Glossar
## Ebene
### Ebene
#### Ebene


- asd
- asdasd 

1. asldkasd
2. askdkasd
    
```Java
public interface Repository<T, ID extends Serializable> {
	T findOne(ID id);
	List<T> findAll();
	T save(T t);	// used for create and update
	void delete(ID id);
	void delete(T entity);
	boolean exists(ID id);
	long count();
}
````

![](sloth.jpg "Micro Service Architektur")
