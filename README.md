# rust-mlops-template

Using included model in binary. See this issue about including PyTorch with binary


Status: Works, but binary cannot pickup PyTorch, so still investigating solutions.


@noahgift ➜ /workspaces/rust-mlops-template/pytorch-binary-cli (main ✗) $ cargo run -- predict --image Walking_tiger_female.jpg 

    Finished dev [unoptimized + debuginfo] target(s) in 0.09s
    
     Running `target/debug/pytorch-binary-cli predict --image Walking_tiger_female.jpg`
     
Current working directory: /workspaces/rust-mlops-template/pytorch-binary-cli

Model path: ../model/resnet18.ot

Model size: 46831783

tiger, Panthera tigris                             90.42%

tiger cat                                           9.19%

zebra                                               0.21%

jaguar, panther, Panthera onca, Felis onca          0.07%

tabby, tabby cat                                    0.03%

