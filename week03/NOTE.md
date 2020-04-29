参考ECMA-262 9.4，下列对象是无法实现出来的：
Function:
	[[Call]](thisArg, argList)
	[[Construct]](argList, newTarget)
Array:
	[[DefineOwnProperty]](P, desc)
String:
	[[GetOwnProperty]](P)
	[[DefineOwnProperty]](P, desc)
	[[OwnPropertyKeys]]()
Argument:
	[[GetOwnProperty]](P)
	[[DefineOwnProperty]](P, desc)
	[[Get]](P, receiver)
	[[Set]](P, V, receiver)
	[[Delete]](P)
Integer-Indexed:
	[[GetOwnProperty]](P)
	[[HasProperty]](P)
	[[DefineOwnProperty]](P, desc)
	[[Get]](P, receiver)
	[[Set]](P, V, receiver)
	[[OwnPropertyKeys]]()
Module:
	[[SetPrototypeOf]](V)
	[[IsExtensible]]()
	[[PreventExtensions]]()
	[[GetOwnProperty]](P)
	[[DefineOwnProperty]](P, desc)
	[[HasProperty]](P)
	[[Get]](P, receiver)
	[[Set]](P, V, receiver)
	[[Delete]](P)
	[[OwnPropertyKeys]]()
Immutable Object:
	[[SetPrototypeOf]](V)
