# Anonymous-invocation-

function func() {
 return this;
}
func() === window; // true
