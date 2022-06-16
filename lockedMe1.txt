package com.lockedme;

public class LockedMeMain {

	private static final MenuOptions MenuOptions = null;

	public static void main(String[] args) {
		
		// Create "main" folder if not present in current folder structure
		FileOperations.createMainFolderIfNotPresent("main");
		
		MenuOptions.printWelcomeScreen();
		
		HandleOptions.handleWelcomeScreenInput();
	}

	
}