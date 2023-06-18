# LoadRunner

Load-Runner is a task runner concept using Bacalhau and provides a platform where the user can chain tasks(built by Devs for royalty fee) allowing non-tech users to be able participate on tech/code heavy operations.

#    
    
    

Bacalhau runs jobs which are containerized and parameterized. This can be extended to be end-user friendly by a platform which manages to chain tasks(to create a flow) without any code use.

The platform(Load-Runner) will have Task Library(build by community devs).

End-users will only need to select a sequential tasks and the the platform will chain them, manage payments and ensure verification on completion. This allows any end-user to be able to run a complex code-related operation once a developer adds it to the library.

Devs are the first on every field and it takes a while for someone to build a decent UI and process to make this work for non-tech users. However, most things are scriptable and can be broken down into smaller tasks, which can be reviewed and verified. Tasks can be chained to provide flexibility to the user. The platform will take up the burden of this.

Funds will be held in smart contracts and will use a bridge for payment to avail off-chain services.

Load-Runner manages the Task Library and provides mechanism to chain tasks and manages payments through smart contracts. It will also provide resources for task chaining such as

- S3 storage for interim data
- Secret/Credential management
- Verification and arbitration
