# QtOutputRedirection
Qt Print Output Redirection．

考虑一下打印加锁
    static QMutex mutex;
    mutex.lock();

    // 解锁
    mutex.unlock();
