1. command to create binary executable - topology_test.test
go test -c

2. run test using binary
./topology_test.test -testbed ../../001_ate_stc.testbed -binding ../../001_ate_stc.binding
./topology_test.test -testbed ../../002_ate_stc.testbed -binding ../../002_ate_stc.binding
./topology_test.test -testbed ../../002_ate_stc.testbed -binding ../../002_ate_stc.binding -alsologtostderr

3. run test using go test command 
go test -testbed ../../002_ate_stc.testbed -binding ../../002_ate_stc.binding
