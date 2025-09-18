# Samsung A55x (SM-A556E) Kernel Manifest

Kernel build manifest for Samsung A55x (SM-A556E)

## Usage

**Create a workspace directory**
   ```bash
   mkdir s5e8845-kernel && cd s5e8845-kernel
   ```

**Initialize the repo**
   ```sh
   repo init -u https://github.com/mst8981/kernel_manifest.git -b main
   ```

**Sync the repositories**
   ```sh
   repo sync
   ```

**Build the kernel**

Once the sync is complete, build the kernel using:
   ```
   ./build.sh
   ```

For more details on building Android kernels with Bazel, see. [Kleaf - Building Android Kernels with Bazel.](https://android.googlesource.com/kernel/build/+/refs/heads/main-kernel/kleaf/README.md)
