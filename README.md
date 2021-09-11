# rustlearn
Learn rust language with a hard way

#### Rust离线阅读：
项目：https://github.com/KaiserY/trpl-zh-cn
cmd: cd /D F:\Git\trpl-zh-cn   
powershell: cd 'F:\Git\trpl-zh-cn'
运行命令:
vuepress dev ./src


#### 待阅读文章：
<1> What is Rust and why is it so popular? : https://stackoverflow.blog/2020/01/20/what-is-rust-and-why-is-it-so-popular/


#### windows下安装
```bash
This will download and install the official compiler for the Rust
programming language, and its package manager, Cargo.

Rustup metadata and toolchains will be installed into the Rustup
home directory, located at:

  C:\Users\win10\.rustup

This can be modified with the RUSTUP_HOME environment variable.

The Cargo home directory located at:

  C:\Users\win10\.cargo

This can be modified with the CARGO_HOME environment variable.

The cargo, rustc, rustup and other commands will be added to
Cargo's bin directory, located at:

  C:\Users\win10\.cargo\bin

This path will then be added to your PATH environment variable by
modifying the HKEY_CURRENT_USER/Environment/PATH registry key.
```



###### 安装完成
```bash
Rust is installed now. Great!

To get started you may need to restart your current shell.
This would reload its PATH environment variable to include
Cargo's bin directory (%USERPROFILE%\.cargo\bin).
```



#### Ubuntu下安装

1. ```shell
   root@DESKTOP-3526GM2:/tmp/rust_install# curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | shinfo: downloading installer
   
   Welcome to Rust!
   
   This will download and install the official compiler for the Rust
   programming language, and its package manager, Cargo.
   
   Rustup metadata and toolchains will be installed into the Rustup
   home directory, located at:
   
     /root/.rustup
   
   This can be modified with the RUSTUP_HOME environment variable.
   
   The Cargo home directory located at:
   
     /root/.cargo
   
   This can be modified with the CARGO_HOME environment variable.
   
   The cargo, rustc, rustup and other commands will be added to
   Cargo's bin directory, located at:
   
     /root/.cargo/bin
   
   This path will then be added to your PATH environment variable by
   modifying the profile files located at:
   
     /root/.profile
     /root/.bashrc
   
   You can uninstall at any time with rustup self uninstall and
   these changes will be reverted.
   
   Current installation options:
   
   
      default host triple: x86_64-unknown-linux-gnu
        default toolchain: stable (default)
                  profile: default
     modify PATH variable: yes
   
   1) Proceed with installation (default)
   2) Customize installation
   3) Cancel installation
   >1
   
   info: profile set to 'default'
   info: default host triple is x86_64-unknown-linux-gnu
   info: syncing channel updates for 'stable-x86_64-unknown-linux-gnu'
   info: latest update on 2021-07-29, rust version 1.54.0 (a178d0322 2021-07-26)
   info: downloading component 'cargo'
   info: downloading component 'clippy'
   info: downloading component 'rust-docs'
   info: downloading component 'rust-std'
   info: downloading component 'rustc'
    50.1 MiB /  50.1 MiB (100 %)  21.2 MiB/s in  2s ETA:  0s
   info: downloading component 'rustfmt'
   info: installing component 'cargo'
   info: installing component 'clippy'
   info: installing component 'rust-docs'
    16.7 MiB /  16.7 MiB (100 %)   2.1 MiB/s in  7s ETA:  0s
   info: installing component 'rust-std'
    21.9 MiB /  21.9 MiB (100 %)  11.3 MiB/s in  2s ETA:  0s
   info: installing component 'rustc'
    50.1 MiB /  50.1 MiB (100 %)  13.0 MiB/s in  3s ETA:  0s
   info: installing component 'rustfmt'
   info: default toolchain set to 'stable-x86_64-unknown-linux-gnu'
   
     stable-x86_64-unknown-linux-gnu installed - rustc 1.54.0 (a178d0322 2021-07-26)
   
   
   Rust is installed now. Great!
   
   To get started you may need to restart your current shell.
   This would reload your PATH environment variable to include
   Cargo's bin directory ($HOME/.cargo/bin).
   
   To configure your current shell, run:
   source $HOME/.cargo/env
   ```

   
