cmake_minimum_required(VERSION 3.20)
project(a10_stefaniamangir_1_main)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(a10_stefaniamangir_1_main
        Action.cpp
        Action.h
        AdminController.cpp
        AdminController.h
        AdminGUI.cpp
        AdminGUI.h
        assignment89TutorialsGUI.cpp
        assignment89TutorialsGUI.h
        CSVRepository.cpp
        CSVRepository.h
        CSVWatchlist.cpp
        CSVWatchlist.h
        CustomTableModel.cpp
        CustomTableModel.h
        Duration.cpp
        Duration.h
        DynamicVector.cpp
        DynamicVector.h
        Exceptions.h
        FileRepository.cpp
        FileRepository.h
        FileRepoWatchlist.cpp
        FileRepoWatchlist.h
        FileWatchlist.cpp
        FileWatchlist.h
        GUI.cpp
        GUI.h
        HTMLRepository.cpp
        HTMLRepository.h
        HTMLWatchlist.cpp
        HTMLWatchlist.h
        main.cpp
        Repository.cpp
        Repository.h
        testController.cpp
        testController.h
        testDynamicVector.cpp
        testDynamicVector.h
        testFileRepo.cpp
        testFileRepo.h
        testRepository.cpp
        testRepository.h
        tests.cpp
        tests.h
        testTutorial.cpp
        testTutorial.h
        testUserController.cpp
        testUserController.h
        testValidator.cpp
        testValidator.h
        testWatchlist.cpp
        testWatchlist.h
        Tutorial.cpp
        Tutorial.h
        UserController.cpp
        UserController.h
        UserGUI.cpp
        UserGUI.h
        Validator.cpp
        Validator.h
        Watchlist.cpp
        Watchlist.h)
