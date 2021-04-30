# major-kit

`
DisplayManager::DisplayManager(sf::RenderTarget& target, sf::RenderWindow& window, World& world, Colony& colony)
	: m_window(window)
	, m_target(target)
	, m_zoom(1.0f)
	, m_offsetX(0.0f)
	, m_offsetY(0.0f)
	, speed_mode(false)
	, m_va(sf::Quads, 0)
	, update(true)
	, debug_mode(false)
	, m_world(world)
	, m_colony(colony)
	, clic(false)
	, m_mouse_button_pressed(false)
	, pause(false)
	, draw_markers(true)
  `
