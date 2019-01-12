package id.curseddev.cursedjoinleave;

import org.bukkit.event.player.PlayerJoinEvent;
import org.bukkit.event.player.PlayerQuitEvent;

public class Main extends org.bukkit.plugin.java.JavaPlugin implements org.bukkit.event.Listener
{
	public Main() {}

	@Override
	public void onEnable()
	{
		getServer().getPluginManager().registerEvents(this, this);
		System.out.println("§f[§cCursed§9JoinLeave§f] §cJoin Leave message disabled!");
		System.out.println("§f[§cCursed§9JoinLeave§f] §fDeveloper : §cCursed Development");
		System.out.println("§f[§cCursed§9JoinLeave§f] §fWebsite : §6https://dev.cursedcraft.id/");
	}

	@org.bukkit.event.EventHandler
	public void onJoin(PlayerJoinEvent JoinMessage) {
		JoinMessage.setJoinMessage(null);
	}

	@org.bukkit.event.EventHandler
	public void onQuit(PlayerQuitEvent QuitMessage) {
		QuitMessage.setQuitMessage(null);
	}
}
