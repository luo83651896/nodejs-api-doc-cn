# 方法和属性

#### 目录操作

* [fs.readdir(path, callback)](#readdir)
* [fs.readdirSync(path)](#readdirSync)
* [fs.mkdir(path[, mode], callback)](#mkdir)
* [fs.mkdirSync(path[, mode])](#mkdirSync)
* [fs.rmdir(path, callback)](#rmdir)
* [fs.rmdirSync(path)](#rmdirSync)
* [fs.realpath(path[, cache], callback)](#realpath)
* [fs.realpathSync(path[, cache])](#realpathSync)

#### 链接操作

* [fs.link(srcpath, dstpath, callback)](#link)
* [fs.linkSync(srcpath, dstpath)](#linkSync)
* [fs.symlink(target, path[, type], callback)](#symlink)
* [fs.symlinkSync(target, path[, type])](#symlinkSync)
* [fs.readlink(path, callback)](#readlink)
* [fs.readlinkSync(path)](#readlinkSync)
* [fs.unlink(path, callback)](#unlink)
* [fs.unlinkSync(path)](#unlinkSync)
* [fs.lchmod(path, mode, callback)](#lchmod)
* [fs.lchmodSync(path, mode)](#lchmodSync)
* [fs.lchown(path, uid, gid, callback)](#lchown)
* [fs.lchownSync(path, uid, gid)](#lchownSync)
* [fs.lstat(path, callback)](#lstat)
* [fs.lstatSync(path)](#lstatSync)

#### 文本流操作

* [fs.createReadStream(path[, options])](#createReadStream)
* [fs.read(fd, buffer, offset, length, position, callback)](#read)
* [fs.readSync(fd, buffer, offset, length, position)](#readSync)
* [fs.createWriteStream(path[, options])](#createWriteStream)
* [fs.write(fd, data[, position[, encoding]], callback)](#write_data)
* [fs.writeSync(fd, data[, position[, encoding]])](#write_data_sync)
* [fs.write(fd, buffer, offset, length[, position], callback)](#write_buffer)
* [fs.writeSync(fd, buffer, offset, length[, position])](#write_buffer_sync)
* [fs.truncate(path, len, callback)](#truncate)
* [fs.truncateSync(path, len)](#truncateSync)
* [fs.watch(filename[, options][, listener])](#watch)
* [fs.stat(path, callback)](#stat)
* [fs.statSync(path)](#statSync)
* [fs.chmod(path, mode, callback)](#chmod)
* [fs.chmodSync(path, mode)](#chmodSync)
* [fs.chown(path, uid, gid, callback)](#chown)
* [fs.chownSync(path, uid, gid)](#chownSync)
* [fs.utimes(path, atime, mtime, callback)](#utimes)
* [fs.utimesSync(path, atime, mtime)](#utimesSync)

#### 文件操作

* [fs.open(path, flags[, mode], callback)](#open)
* [fs.openSync(path, flags[, mode])](#openSync)
* [fs.close(fd, callback)](#close)
* [fs.closeSync(fd)](#closeSync)
* [fs.exists(path, callback)](#exists)
* [fs.existsSync(path)](#existsSync)
* [fs.rename(oldPath, newPath, callback)](#rename)
* [fs.renameSync(oldPath, newPath)](#renameSync)
* [fs.readFile(file[, options], callback)](#readFile)
* [fs.readFileSync(file[, options])](#readFileSync)
* [fs.writeFile(file, data[, options], callback)](#writeFile)
* [fs.writeFileSync(file, data[, options])](#writeFileSync)
* [fs.appendFile(file, data[, options], callback)](#appendFile)
* [fs.appendFileSync(file, data[, options])](#appendFileSync)
* [fs.ftruncate(fd, len, callback)](#ftruncate)
* [fs.ftruncateSync(fd, len)](#ftruncateSync)
* [fs.watchFile(filename[, options], listener)](#watchFile)
* [fs.unwatchFile(filename[, listener])](#unwatchFile)
* [fs.fstat(fd, callback)](#fstat)
* [fs.fstatSync(fd)](#fstatSync)
* [fs.access(path[, mode], callback)](#access)
* [fs.accessSync(path[, mode])](#accessSync)
* [fs.fchmod(fd, mode, callback)](#fchmod)
* [fs.fchmodSync(fd, mode)](#fchmodSync)
* [fs.fchown(fd, uid, gid, callback)](#fchown)
* [fs.fchownSync(fd, uid, gid)](#fchownSync)
* [fs.fdatasync(fd, callback)](#fdatasync)
* [fs.fdatasyncSync(fd)](#fdatasyncSync)
* [fs.futimes(fd, atime, mtime, callback)](#futimes)
* [fs.futimesSync(fd, atime, mtime)](#futimesSync)
* [fs.fsync(fd, callback)](#fsync)
* [fs.fsyncSync(fd)](#fsyncSync)